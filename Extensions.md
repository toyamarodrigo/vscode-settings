## Extensions

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  - Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  -  Auto rename paired HTML/XML tag
- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)
  - Beautify code in place for VS Code
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
  - A customizable extension for colorizing matching brackets
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - Integrates ESLint into VS Code
- [FontSize](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  - Change the font size with keyboard shortcuts.
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
  - View git log, file history, compare branches or commits
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  - Display import/require package size in the editor
- [Intelli Sense](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  - CSS class name completion for the HTML class attribute based on the definitions found in your workspace.
- [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
  -  Language Support for Java™ by Red Hat
  -  Debugger for Java
  -  Java Test Runner
  -  Maven Project Explorer
  -  Java Dependency Viewer
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
  - Code snippets for JavaScript in ES6 syntax
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)
- [Markdown Preview enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
  - Markdown Preview Enhanced ported to vscode
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  - Material Design Icons for Visual Studio Code
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  - Visual Studio Code plugin that autocompletes npm modules in import statements
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
  - Atom's iconic One Dark theme for Visual Studio Code
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  - Visual Studio Code plugin that autocompletes filenames
- [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  - Live Scratchpad for JavaScript.

**For fast instalation create a vscode-extensions.txt and paste all the following extensions in it.**

```
formulahendry.auto-close-tag
formulahendry.auto-rename-tag
hookyqr.beautify
coenraads.bracket-pair-colorizer
dbaeumer.vscode-eslint
fosshaas.fontsize-shortcuts
wix.vscode-import-cost
zignd.html-css-class-completion
xabikos.javascriptsnippets
redhat.java
pkief.material-icon-theme
christian-kohler.npm-intellisense
zhuangtongfa.material-theme
christian-kohler.path-intellisense
wallabyjs.quokka-vscode
yzhang.markdown-all-in-one
shd101wyy.markdown-preview-enhanced
donjayamanne.githistory
vscjava.vscode-java-pack
yzhang.markdown-all-in-one
shd101wyy.markdown-preview-enhanced
```

and then run :
``` 
while read line; do code --install-extension "$line"; done < vscode-extensions.txt
```