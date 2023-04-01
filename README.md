<div align="center">

# 1am Color Theme

### A dark theme for VS Code based on the [Dracula Refined Theme](https://github.com/mathcale/dracula-theme-refined) theme

\
[![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/explodingcamera.1am?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=explodingcamera.1am) [![Open VSX](https://img.shields.io/open-vsx/v/explodingcamera/1am?style=flat-square)](https://open-vsx.org/extension/explodingcamera/1am)

</div>

<br/>

![Screenshot](./image.png)

## Recomended VSCode Settings

> To get the best experience with this theme, I recommend using the [Victor Mono](https://rubjo.github.io/victor-mono/) font and the following settings:

`Settings.json`

```jsonc
{
  "editor.fontFamily": "Victor Mono",
  // only italicize comments (not enabled by default)
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
