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
                "name": "Comment",
                "scope": [ "comment.title.sf" ],
                "settings": {
                    "foreground": "#e0e0e0",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Comment",
                "scope": [ "comment.header.sf" ],
                "settings": {
                    "foreground": "#e0e0e0",
                    "fontStyle": "underline"
                }
            },
            {
                "name": "Comment",
                "scope": [
                    "comment.line.sf",
                    "comment.indented.sf"
                ],
                "settings": {
                    "foreground": "#424242",
                    "fontStyle": "italic"
                }
            },
            {
                "name": "Cancatenation Operator",
                "scope": [ "keyword.operator.concat.sf" ],
                "settings": {
                    "foreground": "#303030",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Dialog Sign",
                "scope": [ "entity.name.type.class.dialog.sign.sf" ],
                "settings": {
                    "foreground": "#1565c0",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Dialog Speaker Name",
                "scope": [ "entity.name.type.class.dialog.text.sf" ],
                "settings": {
                    "foreground": "#2196f3",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Dialog Metadata",
                "scope": [ "entity.name.type.class.dialog.metadata.sf" ],
                "settings": {
                    "foreground": "#64b5f6",
                    "fontStyle": "italic"
                }
            },
            {
                "name": "Dialog Text",
                "scope": [ "string.dialog.sf" ],
                "settings": {
                    "foreground": "#90a4ae"
                }
            },
            {
                "name": "Label Sign",
                "scope": [ "entity.name.namespace.label.sign.sf" ],
                "settings": {
                    "foreground": "#ad1457",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Label Name",
                "scope": [ "entity.name.namespace.label.text.sf" ],
                "settings": {
                    "foreground": "#e91e63",
                    "fontStyle": "bold underline"
                }
            },
            {
                "name": "Label Metadata",
                "scope": [ "entity.name.namespace.label.metadata.sf" ],
                "settings": {
                    "foreground": "#f06292",
                    "fontStyle": "italic"
                }
            },
            {
                "name": "Goto Sign",
                "scope": [ "keyword.control.goto.sign.sf" ],
                "settings": {
                    "foreground": "#4527a0",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Goto Label Name",
                "scope": [ "keyword.control.goto.text.sf" ],
                "settings": {
                    "foreground": "#673ab7",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Goto Metadata",
                "scope": [ "keyword.control.goto.metadata.sf" ],
                "settings": {
                    "foreground": "#b39ddb",
                    "fontStyle": "italic"
                }
            },
            {
                "name": "Options Sign",
                "scope": [ "entity.name.type.enum.option.sign.sf" ],
                "settings": {
                    "foreground": "#c62828",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Options Text",
                "scope": [ "entity.name.type.enum.option.text.sf" ],
                "settings": {
                    "foreground": "#ef5350",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Options Metadata",
                "scope": [ "entity.name.type.enum.option.metadata.sf" ],
                "settings": {
                    "foreground": "#e57373",
                    "fontStyle": "italic"
                }
            },
            {
                "name": "Command Sign",
                "scope": [ "entity.name.function.command.sign.sf" ],
                "settings": {
                    "foreground": "#2e7d32",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Command Label Name",
                "scope": [ "entity.name.function.command.text.sf" ],
                "settings": {
                    "foreground": "#66bb6a",
                    "fontStyle": "bold"
                }
            },
            {
                "name": "Command Metadata",
                "scope": [ "entity.name.function.command.metadata.sf" ],
                "settings": {
                    "foreground": "#a5d6a7",
                    "fontStyle": "italic"
                }
            },
            {
                "name": "Richtext Tag",
                "scope": [ "entity.name.tag.sf" ],
                "settings": {
                    "foreground": "#2196f3",
                    "fontStyle": ""
                }
            },
            {
                "name": "Math Operator",
                "scope": [ "keyword.operator.sf" ],
                "settings": {
                    "foreground": "#757575",
                    "fontStyle": ""
                }
            },
            {
                "name": "Variable",
                "scope": [ "variable.other.property.sf" ],
                "settings": {
                    "foreground": "#b3e5fc",
                    "fontStyle": ""
                }
            },
            {
                "name": "Keyword",
                "scope": [ "constant.language.sf" ],
                "settings": {
                    "foreground": "#2196f3",
                    "fontStyle": ""
                }
            },
            {
                "name": "Tag",
                "scope": [ "variable.other.constant.sf" ],
                "settings": {
                    "foreground": "#ff6e40",
                    "fontStyle": ""
                }
            },
            {
                "name": "Metadata Go To",
                "scope": [ "keyword.control.goto.text.param.sf" ],
                "settings": {
                    "foreground": "#b39ddb",
                    "fontStyle": ""
                }
            },
            {
                "name": "Number",
                "scope": [ "constant.numeric.sf" ],
                "settings": {
                    "foreground": "#008d97",
                    "fontStyle": ""
                }
            },
            {
                "name": "Function",
                "scope": [ "entity.name.function.instruction.sf" ],
                "settings": {
                    "foreground": "#66bb6a",
                    "fontStyle": ""
                }
            },
            {
                "name": "Function Param",
                "scope": [ "variable.parameter.sf" ],
                "settings": {
                    "foreground": "#a5d6a7",
                    "fontStyle": ""
                }
            },
            {
                "name": "String",
                "scope": [ "string.sf" ],
                "settings": {
                    "foreground": "#90a4ae",
                    "fontStyle": ""
                }
            }
        ]
    }
}
```

---
