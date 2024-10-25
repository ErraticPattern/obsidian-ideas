---
creation date: <% tp.file.creation_date() %>
aliases: 
tags:
  - person
modification date: <% tp.file.last_modified_date("dddd, Do MMMM YYYY, HH:mm:ss")%>
status:
---

<%*
let authorName = tp.file.title;
let authorNamePlus = authorName.replace(/ /g, '+');
let authorNameEncoded = encodeURIComponent(authorName);
_%>

## Notes

## Links

- [Google Search](https://www.google.com/search?q=<% authorNamePlus %>)
- [ORCID Search](https://orcid.org/orcid-search/search?searchQuery=<% authorNameEncoded %>)
- [Semantic Scholar](https://www.semanticscholar.org/search?q=<% authorNameEncoded %>&sort=relevance)
- [ResearchGate](https://www.researchgate.net/search?q=<% authorNameEncoded %>)
- [Google Scholar](https://scholar.google.com/scholar?q=<% authorNamePlus %>)

## Backlinking
+ 

## References
+ 
