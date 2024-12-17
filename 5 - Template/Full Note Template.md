---
creation date: <% tp.file.creation_date() %>
aliases: 
tags:
  - baby
modification date: <% tp.file.last_modified_date("dddd, Do MMMM YYYY, HH:mm:ss")%>
id:
---
---

## Parent note
<%*
    let last_file = ""
    let recent_leaf = this.app.workspace.getMostRecentLeaf();
    let back_history = recent_leaf.history.backHistory;
    //skip when there is no back history 
    //this can happen when the file gets created directly from the GUI
    if(back_history.length > 0) {
        // the last entry is the most recent file
        last_file = "[[" + back_history[back_history.length - 1].title + "]]";
    }    
    tR += last_file  ;
_%>


---
## Backlinking


---
# <% tp.file.title %>


---
# Notes

## Definition

## Associations

## Interpretation

---
## Links
- [Google Search](https://www.google.com/search?q=<%* let searchTitle = tp.file.title.replace(/ /g, '+'); tR += searchTitle %>)

---
# References
+ 