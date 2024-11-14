# Changes to Vscode


### Byod addons / Done
* https://hamk-business-information-technology.github.io/os/#step-3-installing-some-useful-vscode-addons

### Byod addons Name / ID / URL
* GitHub Markdown Preview / bierner.github-markdown-preview / 
* Markdown Preview Github Styling / bierner.markdown-preview-github-styles / 
* indent-rainbow / 	oderwat.indent-rainbow	/ https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow 

### Settings User JSON file
You can also review and edit the settings.json file directly by opening it in the editor with the Preferences: Open User Settings (JSON) or Preferences: Open Workspace Settings (JSON) command in the Command Palette (Ctrl+Shift+P).

    "search.followSymlinks": false,


### Settings to Github Repo for forcing to be more usable for students. Force to open in preview mode.

--> .vscode --> settings.json 

    {
        "workbench.startupEditor": "terminal",
        "workbench.editorAssociations": {
            "*.md": "vscode.markdown.preview.editor"
        }
    }



