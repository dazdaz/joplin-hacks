# joplin_hacks


$ cat ~/.config/joplin-desktop/userchrome.css

```
/* For styling the entire Joplin app (except the rendered Markdown, which is defined in `userstyle.css`) */

/* Notebook Font Size */
span.title, span.tag-label {
    font-size: 16px;
}

/* SubNoteBook Font Size */
div.note-list-item > .content > .title > span {
font-size: 16px; font-family: "Caxton Std"; color: black;
}

/* */
.codeMirrorEditor .CodeMirror * {
    font-family: "your font name", monospace !important;
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

https://github.com/alxnbl/onenote-md-exporter
