# just-study

Perhaps do something cool, maybe open source.

## Visual Studio Code

`settings.json`

```json
{
  // theme
  "workbench.colorTheme": "Monokai Pro (Filter Octagon)",
  "workbench.iconTheme": "Monokai Pro (Filter Octagon) Icons",

  // format
  "[typescript][javascript][json][jsonc][css][html][markdown][vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit",
      "source.fixAll.stylelint": "explicit"
    }
  },
  "[python]": {
    "editor.defaultFormatter": "ms-python.autopep8",
    "editor.formatOnSave": true
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {},
  "eslint.validate": [
    "javascript",
    "json",
    "jsonc",
    "typescript",
    "html",
    "vue",
    "markdown"
  ],

  // visual
  "editor.accessibilitySupport": "off",
  "editor.tabSize": 2,
  "editor.wordWrap": "on",

  // minimap
  "editor.minimap.showSlider": "always",
  "editor.minimap.enabled": true,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.size": "fill"
}
```
