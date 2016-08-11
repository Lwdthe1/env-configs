##User settings
```json
{
    "editor.fontSize": 18
}
```

##Keyboard shortcuts
```json
// Place your key bindings in this file to overwrite the defaults
[{
    "key": "cmd+r",
    "command": "editor.action.rename",
    "when": "editorTextFocus"
}
,{
    "key": "shift+left",
    "command": "expandLineSelection",
    "when": "editorTextFocus"
},{
    "key": "shift+right",
    "command": "expandLineSelection",
    "when": "editorTextFocus"
},{
    "key": "ctrl+a",
    "command": "editor.action.selectAll",
    "when": "editorTextFocus"
},{
    "key": "ctrl+f",
    "command": "actions.find",
    "when": "editorTextFocus"
},{
    "key": "ctrl+s",
    "command": "workbench.action.files.save",
    "when": "editorTextFocus"
},{
    "key": "cmd+right",
    "command": "cursorEnd",
    "when": "editorTextFocus"
},{
    "key": "cmd+c",
    "command": "editor.action.clipboardCopyAction",
    "when": "editorTextFocus"
},{
    "key": "cmd+x",
    "command": "editor.action.clipboardCutAction",
    "when": "editorTextFocus"
},{
    "key": "cmd+v",
    "command": "editor.action.clipboardPasteAction",
    "when": "editorTextFocus"
},{
    "key": "ctrl+shift+z",
    "command": "redo",
    "when": "editorTextFocus"
},{
    "key": "ctrl+x",
    "command": "editor.action.clipboardCutAction",
    "when": "editorTextFocus"
},{
    "key": "ctrl+c",
    "command": "editor.action.clipboardCopyAction",
    "when": "editorTextFocus"
},{
    "key": "ctrl+v",
    "command": "editor.action.clipboardPasteAction",
    "when": "editorTextFocus"
},{
    "key": "ctrl+z",
    "command": "undo",
    "when": "editorTextFocus"
}]
```
##Workspace Settings
```json
{
    "search.exclude": {
        "**/.git": true,
        "**/node_modules": true,
        "**/bower_components": true,
        "**/out": true
    }
}
```

