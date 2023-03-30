<div align="center">

# 1am Color Theme

### A dark theme for VS Code based on [Dracula Theme](https://draculatheme.com/visual-studio-code) and [Darkula Theme](https://github.com/mathcale/dracula-theme-refined)

\
[![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/explodingcamera.1am?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=explodingcamera.1am) [![Open VSX](https://img.shields.io/open-vsx/v/explodingcamera/1am?style=flat-square)](https://open-vsx.org/extension/explodingcamera/1am)

</div>

<br/>

![Screenshot](./image.png)

## Recomended VSCode Settings

```jsonc
{
  "editor.fontFamily": "Victor Mono",
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          //following will be in italic (=FlottFlott)
          "comment"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "scope": [
          //following will be excluded from italics (VSCode has some defaults for italics)
          "invalid",
          "keyword.operator",
          "constant.numeric.css",
          "keyword.other.unit.px.css",
          "constant.numeric.decimal.js",
          "constant.numeric.json"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  }
}
```
