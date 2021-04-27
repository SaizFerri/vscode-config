# VS Code Config
### Fonts
[Installation](https://medium.com/@zamamohammed/multiple-fonts-alternative-to-operator-mono-in-vscode-7745b52120a0)
* [Fira code](https://github.com/tonsky/FiraCode)
* [Flottflott](https://www.dafont.com/flottflott.font)
### Theme
One Dark Pro
### Styles
```css
.type.storage,.type.storage.declaration, .storage.class.modifier {
  font-family: 'flottflott';
  font-size: 1.7em;
}

.type.storage.arrow.function {
  font-family: 'Fira Code'
}

.decorator.name, .decorator.punctuation:not(.block), .import.keyword {
  font-family: 'flottflott';
  font-size: 1.7em;
  color: #68f39b!important;
}
.attribute-name {
  font-family: 'flottflott';
  font-style: normal;
  font-size: 1.5em;
}

.mtki {
  font-style: normal;
}

[data-mode-id="javascript"] .mtki,
[data-mode-id="javascript"] .mtk16
{
  font-family: 'flottflott';
  font-size: 1.6em;
  font-style: normal;
}

[data-mode-id="javascript"] .mtk12 {
  font-family: 'Fira code';
  font-size: 1em;
}

[data-mode-id="javascript"] .mtk10 {
  font-family: 'Fira code';
  font-size: 1em;
}

.html.quoted.double {
  color: #a6f3a6!important;
}
.comment {
  font-family: 'flottflott';
  color: #c5c5fd!important;
}
.comment:not(.punctuation) {
  font-family: 'flottflott';
  font-size: 1.5em;
}
```
### Settings
```json
{
  "editor.tabSize": 2,
  "editor.detectIndentation": true,
  "editor.fontSize": 15,
  "editor.fontFamily": "'Fira Code', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "vscode_custom_css.imports": ["file:///home/{$USER}/.vsextension/style.css"],
  "vscode_custom_css.policy": true,
  "prettier.printWidth": 100,
  "prettier.singleQuote": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "window.zoomLevel": 1,
  "editor.formatOnSave": true,
  "[html]": {
    "editor.tabSize": 2,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[twig]": {
    "editor.tabSize": 2
  },
  "[javascript]": {
    "editor.tabSize": 2,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.tabSize": 2
  },
  "[css]": {
    "editor.tabSize": 2
  },
}
```
### Plugins
* [Auto Close tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
* [Auto Rename tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
* [Autoprefixer](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-autoprefixer)
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
* [Custom CSS and JS loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)
* [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)
* [EmojiCode](https://marketplace.visualstudio.com/items?itemName=idleberg.emoji-code)
* [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [File Icons](https://marketplace.visualstudio.com/items?itemName=file-icons.file-icons)
* [IntelliSense for CSS](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
* [Prettify JSON](https://marketplace.visualstudio.com/items?itemName=mohsen1.prettify-json)
* [vscode-pigments](https://marketplace.visualstudio.com/items?itemName=jaspernorth.vscode-pigments)
