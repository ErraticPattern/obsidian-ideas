---
title: "Rules of thumb for minimum sample size for multiple regression"
source: "https://stats.stackexchange.com/questions/10079/rules-of-thumb-for-minimum-sample-size-for-multiple-regression"
author:
  - "[[Cross Validated]]"
published: 2011-04-28
created: 2024-11-12
description: "Within the context of a research proposal in the social sciences, I was asked the following question:I have always gone by 100 + m (where mis the number of predictors) whendetermining minimum s..."
tags:
  - "clippings"
---
I don't prefer to think of this as a power issue, but rather ask the question "how large should $n$ be so that the apparent $R^{2}$ can be trusted"? One way to approach that is to consider the ratio or difference between $R^{2}$ and $R_{a d j}^{2}$, the latter being the adjusted $R^{2}$ given by $1 - \left(\right. 1 - R^{2} \left.\right) \frac{n - 1}{n - p - 1}$ and forming a more unbiased estimate of "true" $R^{2}$.

Some R code can be used to solve for the factor of $p$ that $n - 1$ should be such that $R_{a d j}^{2}$ is only a factor $k$ smaller than $R^{2}$ or is only smaller by $k$.

```
require(Hmisc)
dop <- function(k, type) {
  z <- list()
  R2 <- seq(.01, .99, by=.01)
  for(a in k) z[[as.character(a)]] <-
    list(R2=R2, pfact=if(type=='relative') ((1/R2) - a) / (1 - a) else
         (1 - R2 + a) /  a)
  labcurve(z, pl=TRUE, ylim=c(0,100), adj=0, offset=3,
           xlab=expression(R^2), ylab=expression(paste('Multiple of ',p)))
}
par(mfrow=c(1,2))
dop(c(.9, .95, .975), 'relative')
dop(c(.075, .05, .04, .025, .02, .01), 'absolute')
```

![enter image description here](https://i.sstatic.net/celfT.png) Legend: Degradation in $R^{2}$ that achieves a relative drop from $R^{2}$ to $R_{a d j}^{2}$ by a the indicated relative factor (left panel, 3 factors) or absolute difference (right panel, 6 decrements).

If anyone has seen this already in print please let me know.