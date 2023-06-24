# A QuickCopy Template for Exporting Zotero Items to Markdown Files

Here I provided an [ETA](https://eta.js.org/) template for [better bibtex](https://github.com/retorquere/zotero-better-bibtex) users 
to drag-and-drop [Zotero](https://github.com/zotero/zotero) items directly into Markdown files like:

```text
[Author, Year](zotero_link)
```

Which may be rendered as "`[Author, Year`]" in markdown files. 
By coping this template to BBT's option -> Export -> Quick-Copt -> Eta templates, you could use BBT's QuickCopy feature to create easy-reading links in markdown files that associate the "author-year" mark with the corresponding Zotero item.

What may look confusing is that this template exported both the lastName and the name of creator while replacing all "undefined". 
This manipulation allows Asian names (like Chinese names) could be exported as a whole (e.g., "MaoZeDong" instead of "ZeDong, Mao") to meet the academic customs of these areas,
especially after the batch modification of [jasminum](https://github.com/l0o0/jasminum).

Hope this little template accelerates your note-taking experience when reading papers :)

