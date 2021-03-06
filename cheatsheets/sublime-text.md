# Sublime Text

### Preference.sublime-settings - User

```json
{
    "binary_file_patterns":
    [
        "*min.js",
        "*.debug.js",
        "*prod.js"
    ],
    "color_scheme": "Packages/Color Scheme - Default/Monokai.tmTheme",
    "folder_exclude_patterns":
    [
        "tmp",
        "assets",
        "node_modules",
        "bower_components"
    ],
    "font_size": 14,
    "ignored_packages":
    [
        "Vintage"
    ],
    "rulers":
    [
        90
    ],
    "tab_size": 4,
    "translate_tabs_to_spaces": true
}

```

### Shorcut Keys

On Menu Bar: **Sublime Text > Preferences > Key Bindings - User**

```json
[{
    "keys": ["alt+up"],
    "command": "scroll_lines",
    "args": {
        "amount": 30.0
    }
}, {
    "keys": ["alt+down"],
    "command": "scroll_lines",
    "args": {
        "amount": -30.0
    }
}, { "keys": ["alt+s"], "command": "toggle_in_selection",
    "context": [{"key": "panel", "operand": "replace"}, {"key": "panel_has_focus"}]
}]
```

### 3rd Party Packages

[Install package control](https://packagecontrol.io/installation)

[PEP8 Autoformat](https://packagecontrol.io/packages/Python%20PEP8%20Autoformat)

[HTMLBeautify](https://packagecontrol.io/packages/HTMLBeautify)

[Javascript Beautify](https://packagecontrol.io/packages/Javascript%20Beautify)

### Show hidden dot files

`cmd + shift + .`

