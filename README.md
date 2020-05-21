# Snowfall VSCode Extension

This extension provides syntax highlighting for _Snowfall Storytelling Language_, within [Visual Studio Code](https://code.visualstudio.com/).

---

## Snowfall Storytelling Language

_Snowfall Storytelling Language_ is a simple markup language, used to write interactive stories using [Snowfall Storytelling Plugin](https://snowfalldoc.web.app/).

---

## Code Coloring

Add this to your __settings.json__, for better code coloring.

```json
{
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "name": "Comments scene title lines",
                "scope": [
                    "strong.comment.title.sf"
                ],
                "settings": {
                    "foreground": "#D9D9D9",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Comments scene header lines",
                "scope": [
                    "markup.underline.comment.header.sf"
                ],
                "settings": {
                    "foreground": "#D9D9D9",
                    "fontStyle": "bold underline"
                }
            },
            {
                "name": "Comments and simple lines",
                "scope": [
                    "markup.italic.comment.line.sf"
                ],
                "settings": {
                    "foreground": "#5A5A5A",
                    "fontStyle": "italic"
                }
            },
            {
                "name": "Label",
                "scope": [
                    "entity.name.type.label.sf"
                ],
                "settings": {
                    "foreground": "#ec407a",
                    "fontStyle": "bold underline"
                }
            },
            {
                "name": "Dialog Tags",
                "scope": [
                    "markup.heading.dialog.metadata.sf"
                ],
                "settings": {
                    "foreground": "#2196f3"
                }
            },
            {
                "name": "Dialog Text",
                "scope": [
                    "variable.dialog.data.sf"
                ],
                "settings": {
                    "foreground": "#78909c"
                }
            },
            {
                "name": "Player Option",
                "scope": [
                    "invalid.option.sf"
                ],
                "settings": {
                    "foreground": "#ef5350"
                }
            },
            {
                "name": "Script Command",
                "scope": [
                    "comment.command.sf"
                ],
                "settings": {
                    "foreground": "#66bb6a",
                    "fontStyle": "italic"
                }
            },
            {
                "name": "Go To Label",
                "scope": [
                    "keyword.control.goto.sf"
                ],
                "settings": {
                    "foreground": "#9575cd"
                }
            }
        ]
    }
}
```

---
