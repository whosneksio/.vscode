## Preview

![preview](https://raw.githubusercontent.com/whosneksio/.vscode/main/preview.png)

## Extensions

### Theming

- Vesper ++
- Symbols

### Utility

- GitHub Pull Requests
- Prettier
- Pretter ESLint
- Database Client
- Database Client JDBC
- Claude Code for VS Code

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
    "workbench.colorTheme": "Vesper ++",

    "window.zoomLevel": 0.35,
    "window.commandCenter": false,
    "window.title": "${dirty}${activeEditorShort}$ ~ ${rootName}${separator}${profileName}${separator}",

    "explorer.compactFolders": false,

    "breadcrumbs.enabled": false,
    "workbench.activityBar.location": "top",
    "window.menuBarVisibility": "compact",
    
    "claudeCode.useTerminal": true,
    "git.autofetch": true
}
```

## Claude's settings.json

```json
{
  "env": {
    "ANTHROPIC_BASE_URL": "",
    "ANTHROPIC_AUTH_TOKEN": "",
    "CLAUDE_CODE_DISABLE_NONESSENTIAL_TRAFFIC": "1",
    "CLAUDE_CODE_ATTRIBUTION_HEADER": "0",
    "DISABLE_TELEMETRY": "1",
    "DISABLE_ERROR_REPORTING": "1",
    "DISABLE_AUTOUPDATER": "1",
    "DISABLE_BUG_COMMAND": "1",
    "DISABLE_COST_WARNINGS": "1",
    "DISABLE_NON_ESSENTIAL_MODEL_CALLS": "1"
  },
  "permissions": {
    "defaultMode": "bypassPermissions"
  },
  "model": "",
  "enabledPlugins": {
    "claude-code-setup@claude-plugins-official": true
  },
  "effortLevel": "low",
  "autoUpdatesChannel": "latest",
  "skipDangerousModePermissionPrompt": true,
  "theme": "dark"
}
```
