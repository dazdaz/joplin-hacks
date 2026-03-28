# joplin_hacks

### Settings / Appearance / Preferred Dark Theme / Light

$ cat ~/.config/joplin-desktop/userchrome.css

```
/* For styling the entire Joplin app (except the rendered Markdown, which is defined in `userstyle.css`) */

/* Notebook Font Size */
span.title, span.tag-label {
    font-size: 16px;
}

/* SubNoteBook Font Size */
div.note-list-item > .content > .title > span {
font-size: 16px; font-family: "Times New Roman"; color: black;
}

/* */
.codeMirrorEditor .CodeMirror * {
    font-family: "Times New Roman", monospace !important;
}

/* NoteBooks - White Background */
.sidebar {
   background-color: purple! important;
}

/* Black Font Color for NoteBooks */
span.title, span tag-label {
    color: white! important;
}
```

# $ cat ~/.config/joplin-desktop/userchrome.css
```
/* For styling the entire Joplin app (except the rendered Markdown, which is defined in `userstyle.css`) */

/* Notebook Font Size */
span.title, span.tag-label {
    font-size: 16px;
}

/* SubNoteBook Font Size */
div.note-list-item > .content > .title > span {
font-size: 16px; font-family: "Times New Roman"; color: black;
}

/* */
.codeMirrorEditor .CodeMirror * {
    font-family: "your font name", monospace !important;
}

/* NoteBooks - Purple Background */
.sidebar {
   background-color: purple! important;
}

/* White Font Color for NoteBooks */
span.title, span.tag-label {
    color: white! important;
}

/* Note List Pane - White Background */
div.note-list,
.rli-noteList,
.rli-noteList > div,
.rli-noteList > div > div,
.rli-noteList > div > div > div,
.list-item-container,
.list-item,
.note-list-item,
div.note-list-item {
    background-color: white !important;
    color: black !important;
}

/* Editor Pane - White Background */
.rli-editor {
    background-color: white !important;
    color: black !important;
}
```

https://github.com/alxnbl/onenote-md-exporter
https://discourse.joplinapp.org/
