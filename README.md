# VS Code Config
### Fonts
[Installation](https://medium.com/@zamamohammed/multiple-fonts-alternative-to-operator-mono-in-vscode-7745b52120a0)
* [Fira code](https://github.com/tonsky/FiraCode)
* [Flottflott](https://www.dafont.com/flottflott.font)
### Theme
Monokai Pro
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
  "[html]": {
      "editor.tabSize": 4
  }
}
```
### Plugins
* [Auto Close tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
* [Auto Rename tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
* [Autoprefixer](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-autoprefixer)
* [Custom CSS and JS loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
* [Prettify JSON](https://marketplace.visualstudio.com/items?itemName=mohsen1.prettify-json)
* [vscode-pigments](https://marketplace.visualstudio.com/items?itemName=jaspernorth.vscode-pigments)
* [IntelliSense for CSS](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
