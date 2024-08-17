# Json configs
```json
{
  "workbench.iconTheme": "symbols",
  "explorer.confirmDelete": false,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.letterSpacing": 0.25,
  "editor.lineHeight": 1.8,
  "editor.rulers": [80, 120],
  "workbench.startupEditor": "newUntitledFile",
  "editor.renderLineHighlight": "gutter",
  "workbench.editor.labelFormat": "short",
  "explorer.compactFolders": false,
  "editor.semanticHighlighting.enabled": false,
  "breadcrumbs.enabled": false,
  "workbench.activityBar.location": "hidden",
  "editor.minimap.enabled": false,
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.vertical": "hidden",
  "editor.lineNumbers": "off",
  "window.titleBarStyle": "native",

  "apc.activityBar": {
    "position": "bottom",
    "hideSettings": true,
    "size": 48,
    "itemMargin": 8,
    "itemSize": 32
  },
  "editor.hideCursorInOverviewRuler": true,
  "apc.electron": {
    "titleBarStyle": "hiddenInset",
    "trafficLightPosition": {
      "x": 11,
      "y": 10
    },
    "opacity": 1,
    "vibrancy": "dark",
    "frame": false
  },
  "apc.header": {
    "height": 36
  },
  "apc.listRow": {
    "height": 24
  },
  "apc.font.family": "Inter",
  "apc.stylesheet": {
    ".title-label > h2": "display: none",
    ".editor-actions": "display: none",
    ".nosidebar .inline-tabs-placeholder": "width: 75px",
    ".pane-header": "padding: 0 8px",
    ".pane-body": "padding: 8px",
    ".split-view-view:first-child .pane-header": "display: none !important;",
    ".monaco-list-row": "border-radius: 4px;",
    ".monaco-workbench .monaco-list:not(.element-focused):focus:before": "display: none;"
  },

  "explorer.sortOrder": "foldersNestsFiles",
  "explorer.fileNesting.patterns": {
    "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-*, bun.lockb, nest*, package-lock*",
    "tailwind.config.*": "tailwind.config*, postcss.config*",
    ".env.local": ".env*",
    ".env": ".env*"
  },
  "explorer.fileNesting.enabled": true,
  "editor.tokenColorCustomizations": {
    "textMateRules": []
  },

  "workbench.colorCustomizations": {
    "[Dracula]": {
      "editor.background": "#1c1e25",
      "activityBar.background": "#191a22",
      "sideBar.background": "#191a22",
      "activityBar.foreground": "#77d7fd"
    },
    "statusBar.background": "#9f00a6",
    "statusBar.noFolderBackground": "#8a008f",
    "statusBar.debuggingBackground": "#8a008f",
    "statusBar.foreground": "#ffffff",
    "statusBar.debuggingForeground": "#ffffff"
  },
  
  "diffEditor.ignoreTrimWhitespace": false,
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.enableMultiLinePasteWarning": false,
  "editor.formatOnSave": true,
  "[typescriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "liveServer.settings.donotShowInfoMsg": true,

  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 125,

  "editor.insertSpaces": true,
  "editor.tabSize": 2,
  "editor.cursorBlinking": "expand",
  "[python]": {
    "editor.formatOnType": true
  },
  "errorLens.excludeBySource": ["Pylance(reportUndefinedVariable)"],
  "errorLens.onSave": true,
  "errorLens.messageEnabled": false,
  "terminal.integrated.env.windows": {},
  "symbols.hidesExplorerArrows": false,
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.statusBar.visible": false,
  "workbench.list.smoothScrolling": true,
  "editor.smoothScrolling": true,
  "workbench.sideBar.location": "right",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.layoutControl.enabled": false,
  "window.commandCenter": false,
  "window.menuBarVisibility": "compact",
  "workbench.colorTheme": "Min Dark"
}
```

# VSCode Extensions
* Themes
  * Min Dark
  * Dracula
  * Material Icon Theme
* HTML -> CSS
  * Auto Rename Tag
  * Color Highlight
  * CSS Modules
  * Live Sass Compiler
  * Sass
  * styled-components-snippets
  * vscode-styled-components
* Javascript
  * ESLint
  * Code Spell Checker
  * ES7+ React/Redux/React-Native snippets
  * Simple React Snippets
* Addons
  * Bookmarks
  * Codesnap
  * Discord Presence
  * Emoji
  * GitLens
  * Settings Sync  (Disable)
  * Status Bar Customizer
  * Expo Tools
