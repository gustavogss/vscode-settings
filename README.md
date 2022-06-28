# VsCode - settings.json :tools
Configurações do VsCode
```
{
  // Define o tema do VSCode
  "workbench.colorTheme": "Dracula",

  // Configura tamanho e família da fonte
  "editor.fontSize": 14,
  "editor.lineHeight": 24,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true, 
  "editor.wordWrap": "on",
  "editor.defaultFormatter": "esbenp.prettier-vscode",  
  "telemetry.telemetryLevel": "off",  
  "security.workspace.trust.untrustedFiles": "open",
  "breadcrumbs.filePath": "off",
  "outline.icons": false, 
  "liveServer.settings.donotVerifyTags": true,
  "html.autoClosingTags": false,

  // Aplica linhas verticais para lembrar de quebrar linha em códigos muito grandes
  "editor.rulers": [80, 120],
  "prettier.eslintIntegration": true,

  // Aplica um sinal visual na esquerda da linha selecionada
  "editor.renderLineHighlight": "gutter",

  // Aumenta a fonte do terminal
  "terminal.integrated.fontSize": 14,

  // Define o tema dos ícones na sidebar
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "none",
  "editor.tabSize": 2,
  "tslint.autoFixOnSave": true,
  "window.zoomLevel": 0,
  "extensions.ignoreRecommendations": false,
  "emmet.syntaxProfiles": {
    "javascript": "jsx",
    "nunjucks": "html"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "nunjucks": "html"
  },
  "javascript.updateImportsOnFileMove.enabled": "never",
  "gitlens.codeLens.recentChange.enabled": false,
  "gitlens.codeLens.authors.enabled": false,
  "gitlens.codeLens.enabled": false,
  "breadcrumbs.enabled": true,
  "git.enableSmartCommit": true,
  "editor.parameterHints.enabled": false,
  "typescript.updateImportsOnFileMove.enabled": "never",
  "prettier.tslintIntegration": true,
  "bracket-pair-colorizer-2.depreciation-notice": false,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "java.jdt.ls.vmargs": "-XX:+UseParallelGC -XX:GCTimeRatio=4 -XX:AdaptiveSizePolicyWeight=90 -Dsun.zip.disableMemoryMapping=true -Xmx1G -Xms100m -javaagent:\"/home/gustavosouza/.vscode/extensions/gabrielbb.vscode-lombok-1.0.1/server/lombok.jar\"",
  "redhat.telemetry.enabled": true,
  "peacock.favoriteColors": [
    {
      "name": "Angular Red",
      "value": "#dd0531"
    },
    {
      "name": "Azure Blue",
      "value": "#007fff"
    },
    {
      "name": "JavaScript Yellow",
      "value": "#f9e64f"
    },
    {
      "name": "Mandalorian Blue",
      "value": "#1857a4"
    },
    {
      "name": "Node Green",
      "value": "#215732"
    },
    {
      "name": "React Blue",
      "value": "#61dafb"
    },
    {
      "name": "Something Different",
      "value": "#832561"
    },
    {
      "name": "Svelte Orange",
      "value": "#ff3d00"
    },
    {
      "name": "Vue Green",
      "value": "#42b883"
    }
  ],
  "liveServer.settings.donotShowInfoMsg": true,
  "thunder-client.codeSnippetLanguage": "cs-httpclient",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  
  "explorer.compactFolders": false,
  "[dockercompose]": {
    "editor.defaultFormatter": "ms-azuretools.vscode-docker"
  }
}
```