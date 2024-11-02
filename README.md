# Vault Organization

## 0 - Supplementary
This is where image files and other kinds of media will be saved. Vault related files will be stored here.
+ **Queries**
Queries will make use of the `Charts` plugin to better understand the notes and their inter-relationship in my vault.
## 1 - Rough Notes
This is where I will keep rough notes and [[Reminders]]. Information from these can then be added to relevant notes in the "Zettelkasten" folder. 
- **Meetings**
Use the `Daily Note` plugin followed by the meeting/tasks templates to quickly create a note for note taking.
- **Experiments**
Make use of the plugin `Tasks` and its feature of adding emojis for selective fetching of tasks.
## 2 - Source Materials
This folder is where I will store my insights about different source materials such as books, videos, podcasts, etc.; anything from which I can obtain knowledge. 
+ **Articles:**
Text from articles can be highlighted in Zotero and imported to obsidian via the [[Zotero Template]]. Check [[Article Highlighting]] to understand the meaning of which color (highlighting in zotero was done with the `Highlightr` plugin). 
+ **Word Documents:**
One main source of information are my word documents which I used in the past to curate information. I can use the `docxer` and `note refactor` plugins to quickly add the information into my obsidian framework.
## 3 - Tags
This is where I will keep my tags (empty notes) which serve to connect different notes with converging ideas.
## 4 - Indexes
When a specific tag starts linking a lot of notes, then I can move that tag into the this folder. I can then fill this tag with information about general topics which the notes cover and us this tag as a table of content.
## 5 - Template
This is where templates for my notes will exist. The "Full Note" template assigns a status parameter which can have "baby", "child", and "adult" values to denote the status of completion of the note. Other templates are useful for more specific functions such as interaction with other vault notes (`vault template`).
## 6 - Zettelkasten
This is where my main notes will exist. Each note will be assigned a template. All zettelkasten notes will have at least one of three kinds of development tags: `baby`, `children`, `adult`. These are ordered in increasing degrees of note development. The main advantage of this system is that using the `Smart Random Note` plugin, it is possible to search one random note out of all those with a specific tag and then develop and research more about that note. The ultimate goal is to have as many adult notes as possible.
## Web
This is a (temporary) folder holding information scrapped from the web using the `web clipper` plugin and browser extension.
## Other Points
1. Status: Refers to the state of the note (baby, child, adult) and can be used to group notes by general topics (e.g. [[Neuroscience]]).
2. Try to keep notes with less than 500 words for readability.
3. Use ```Ctrl+O``` for notes and querying.
4. Use ```Ctrl+A``` for template setting.
5. Use ```Ctrl+T``` for opening a new tab.
6. Use Hotkeys to add templates faster. `Ctrl+Shift+Q` for quotes. `Ctrl+Shift+X`  for figures.
7. Add gifs by dragging from the web page or saving it as a gif.
8. It is possible to create internal links, be it inside the same note using `[[^]]` or for different notes using `[[^^]]`, e.g. [[Windows Setup#^537f7f]]. Remember to use the pipe operator to create an alias for the link name, such as [[Windows Setup#^537f7f|Obsidian]]. The advantage of this feature is the possibility to link directly note's sections or links.
---
# Plugins
## Using *Zotero* 
Check the [[Research Workflow]] note to understand how to implement Zotero for productive references management. 
**Requirements:**
+ *Better bibtex* addon for Zotero (available on GitHub).
+ *ZoteroDuplicateMeger* addon for Zotero (available on GitHub).
+ Zotero Integration plugin in obsidian.
**How to cite (full and short citation):**
1. Open a note.
2. Copy citation/bibliography in Zotero.
3. `Ctrl+P` and type "Zotero".
4. Select desired option.
*Note: Current citation style is set as APA 7.*
**How to add annotations:** -> ==***This step is no longer required after the latest updates.***==
1. Create note from annotation in Zotero.
2. Import annotations in Obsidian using `Ctrl+P` and type "Zotero".
**Add-ons:**
Installed `Tesseract-OCR` to perform text recognition (OCR = optical character recognition)-[link here](https://github.com/UB-Mannheim/tesseract/wiki). Create also a template to get all the metadata from papers.
## Using *Templater*
To use a template from *templater* you have to create a note from *templater*. You can use the hotkey `Alt+N` to create a new note with the template. To apply the template to an existing note search for it using `Ctrl+P` or use the templater icon in the top-left corner. Using templater you can:
+ Create lab notes.
### Using *Git*
Initiate a git repository in you obsidian folder. If it fails to push your commits than it is most likely due to a problem in permission. Most likely you have another associated account other than the one which is associated with the remote repository. To solve this go on `Manage Windows Credentials` and input your correct credentials in the Github section.
## Using *Tasks*
Use tasks to organize future assignments.
## Linking Notes
**Inside Vaults:**
You can use the Note Linker plugin to automatically create backlinks between notes. 
**Between Vaults:**
Furthermore, it is possible to link notes between vaults using the Advanced URI plugin. This can be done by adding the URI link or dragging the note to the vault.
## Using *Advanced Tables*
Don't forget to enable source mode otherwise hitting tab will only indent the current row. You can also export as a `csv` file by copying the formatted text to a file and importing from excel.

---
# To do
- [x] Create a script to automatically send images from the root of the vault to `0 - Supplementary/images`. ✅ 2024-10-03
- [x] Update the `Experiment Template` to now show tasks if the experiment has finished. ✅ 2024-10-03