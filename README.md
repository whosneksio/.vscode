## Preview

![preview](https://raw.githubusercontent.com/whosneksio/.vscode/main/preview.png)

## Extensions

### Theming

- [Apc Customize UI++](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension)
- [Borderless Tokyo Night](https://marketplace.visualstudio.com/items?itemName=gusvasconcelos.borderless-tokyonight)
- [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)

### Utility

- [Discord Rich Presence](https://marketplace.visualstudio.com/items?itemName=LeonardSSH.vscord)
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Ruff](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff)

## settings.json

```json
{
    "terminal.integrated.smoothScrolling": true,
    "terminal.integrated.fontFamily": "JetBrains Mono",
    "terminal.integrated.fontSize": 18,

    "editor.fontSize": 18,
    "editor.fontFamily": "JetBrains Mono",
    "editor.wordWrap": "on",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.smoothScrolling": true,
    "editor.cursorBlinking": "phase",
    "editor.lineHeight": 1.5,
    "editor.renderLineHighlight": "gutter",
    "editor.minimap.enabled": false,

    "editor.defaultFormatter": "esbenp.prettier-vscode",

    "workbench.iconTheme": "symbols",
    "workbench.list.smoothScrolling": true,
    "workbench.layoutControl.enabled": false,
    "workbench.colorTheme": "Borderless Tokyo Night",

    "window.zoomLevel": 0.35,
    "window.commandCenter": false,
    "window.title": "${dirty}${activeEditorShort}$ ~ ${rootName}${separator}${profileName}${separator}",

    "explorer.compactFolders": false,

    "breadcrumbs.enabled": false,

    "apc.statusBar": {
        "height": 24,
        "fontSize": 12
    },

    "apc.header": {
        "height": 36
    },

    "apc.listRow": {
        "height": 24
    },

    "apc.stylesheet": {
        ".title-label > h2": "display: none;",
        ".editor-actions": "opacity: 0.1; transition: .2s;",
        ".editor-actions:hover": "opacity: 1; transition: .2s;",
    },

    "apc.font.family": "Inter",
}
```
