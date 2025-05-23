{
  "window.zoomLevel": -1,
  "workbench.colorTheme": "Min Dark",
  "symbols.hidesExplorerArrows": false,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.8,
  "editor.rulers": [80, 100, 120],
  "files.autoSave": "afterDelay",
  "workbench.startupEditor": "newUntitledFile",
  "editor.renderLineHighlight": "gutter",
  "workbench.editor.labelFormat": "short",
  "scm.compactFolders": false,
  "editor.semanticHighlighting.enabled": false,
  "workbench.activityBar.location": "hidden",
  "editor.minimap.enabled": false,
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.horizontal": "hidden",
  "workbench.statusBar.visible": false,
  "window.titleBarStyle": "native",
  "security.workspace.trust.untrustedFiles": "open",
  "explorer.compactFolders": false,
  "explorer.fileNesting.enabled": false,
  "workbench.tree.indent": 25,
  "apc.electron": {
    "titleBarStyle": "hiddenInset"
  },
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,
  "window.menuBarVisibility": "hidden",
  "workbench.iconTheme": "symbols",
  "extensions.ignoreRecommendations": true,

  // ESLint
  "eslint.enable": true,
  "eslint.validate": ["javascript", "javascriptreact", "typescript", "typescriptreact"],
  "eslint.alwaysShowStatus": true,
  "eslint.format.enable": false,

  // Corrigir automaticamente (inclusive linhas em branco)
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit",
    "source.fixAll.eslint": "explicit"
  },

  // Prettier desativado para JS/TS (usando ESLint)
  "prettier.disableLanguages": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],

  // Prettier como formatador principal para outras linguagens
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "prettier.printWidth": 300,
  "prettier.arrowParens": "avoid",
  "prettier.bracketSpacing": true,

  // Formatadores por linguagem
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[sql]": {
    "editor.defaultFormatter": "inferrinizzard.prettier-sql-vscode",
    "editor.formatOnSave": true
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // Importações relativas
  "typescript.preferences.importModuleSpecifier": "relative",
  "javascript.preferences.importModuleSpecifier": "relative",

  // Emmet
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },

  // Import Cost
  "importCost.largePackageColor": "#ff0000",
  "importCost.mediumPackageColor": "#ffa500",
  "importCost.smallPackageColor": "#00ff00",

  // TypeScript do workspace
  "typescript.enablePromptUseWorkspaceTsdk": true,
  "typescript.tsdk": "node_modules/typescript/lib",

  // Desativa validação JS nativa
  "javascript.validate.enable": false,
  "typescript.validate.enable": true,

  // Associações de arquivos
  "files.associations": {
    "*.tsx": "typescriptreact",
    "*.ts": "typescript",
    "*.jsx": "javascriptreact"
  },

  // Sugestões automáticas
  "editor.quickSuggestions": {
    "other": true,
    "comments": false,
    "strings": true
  },

  // Formatar ao salvar
  "editor.formatOnSave": true
}
