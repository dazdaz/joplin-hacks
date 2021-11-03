# joplin_hacks


$ cat ~/.config/joplin-desktop/userchrome.css

```
/* For styling the entire Joplin app (except the rendered Markdown, which is defined in `userstyle.css`) */

/* Notebook Font Size */
span.title, span.tag-label {
    font-size: 16px;
}

/* SubNoteBook Font Size */
.note-list-item > a > span {
    font-size:15px;
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
