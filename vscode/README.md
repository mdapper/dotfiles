# VS Code

## Themes

- [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
- [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

## Plugins

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Babel JavaScript](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [Brazilian Portuguese - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese-brazilian)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [colorize](https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize)
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [Duplicate action](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-duplicate)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [ElixirLS: Elixir support and debugger](https://marketplace.visualstudio.com/items?itemName=JakeBecker.elixir-ls)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Flow Language Support](https://marketplace.visualstudio.com/items?itemName=flowtype.flow-for-vscode)
- [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [GraphQL for VSCode](https://marketplace.visualstudio.com/items?itemName=kumar-harsh.graphql-for-vscode)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [MDX](https://marketplace.visualstudio.com/items?itemName=silvenon.mdx)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Sass](https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented)
- [Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)
- [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)
- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)

## Configs

```json
{
  "cSpell.language": "en,pt-BR",
  "diffEditor.ignoreTrimWhitespace": true,

  "editor.fontFamily": "Dank Mono",
  "editor.fontLigatures": true,
  "editor.fontSize": 18,
  "editor.formatOnSave": false,
  "editor.renderWhitespace": "boundary",
  "editor.suggestSelection": "first",
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.wrappingIndent": "indent",

  "explorer.openEditors.visible": 0,

  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "files.trimTrailingWhitespace": true,

  "gitlens.codeLens.enabled": false,
  "gitlens.hovers.enabled": false,
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true
  },

  "terminal.integrated.fontFamily": "Dank Mono",
  "terminal.integrated.fontSize": 16,

  "workbench.colorTheme": "Night Owl",
  "workbench.editor.closeOnFileDelete": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.panel.defaultLocation": "right",
  "workbench.startupEditor": "newUntitledFile",

  "prettier.singleQuote": true,
  "prettier.trailingComma": "es5",
  "prettier.arrowParens": "always",
  "[javascript]": {
    "editor.formatOnSave": true
  },
  "[javascriptreact]": {
    "editor.formatOnSave": true
  },
  "[typescript]": {
    "editor.formatOnSave": true
  },
  "[typescriptreact]": {
    "editor.formatOnSave": true
  },
  "[json]": {
    "editor.formatOnSave": false
  },
  "[markdown]": {
    "editor.formatOnSave": true
  },
  "[graphql]": {
    "editor.formatOnSave": true
  },

  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
  },
  "files.watcherExclude": {
    "**/.git/objects/**": true,
    "**/.git/subtree-cache/**": true,
    "**/node_modules/*/**": true
  },
  "colorize.languages": [
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ]
}
```
