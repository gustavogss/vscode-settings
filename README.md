# VsCode - settings.json :hammer_and_pick:
Configurações do VsCode
```
{
  // Aparência do editor
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Ayu Dark",
  "workbench.productIconTheme": "fluent-icons",
  "explorer.compactFolders": false,
  "editor.minimap.enabled": false,
  // Configuração da fonte
  "editor.fontFamily": "'Fira Code'",
  "editor.fontLigatures": true,
  "editor.fontSize": 15,
  "editor.lineHeight": 26,
  "editor.tabSize": 2,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
  },
  // Formatação de código
  "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "es5",
  "prettier.semi": false,
  // Formatação por tipo de arquivo
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[yaml]": {
    "editor.defaultFormatter": "redhat.vscode-yaml"
  },
  // Configuração para Emmet
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  // Suporte para Dart
  "[dart]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.rulers": [
      80
    ],
    "editor.selectionHighlight": false,
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": "off"
  },
  // Configurações de extensões
  "tabnine.experimentalAutoImports": true,
  "database-client.autoSync": true,
  // Configuração de agrupamento no explorador
  "explorer.fileNesting.patterns": {
    "*.ts": "${capture}.js",
    "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
    "*.jsx": "${capture}.js",
    "*.tsx": "${capture}.ts",
    "tsconfig.json": "tsconfig.*.json",
    "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb",
    "*.sqlite": "${capture}.${extname}-*",
    "*.db": "${capture}.${extname}-*",
    "*.sqlite3": "${capture}.${extname}-*",
    "*.db3": "${capture}.${extname}-*",
    "*.sdb": "${capture}.${extname}-*",
    "*.s3db": "${capture}.${extname}-*"
  },
  // Python (desabilitar criação de ambientes automáticos)
  "python.createEnvironment.trigger": "off"
}

```
