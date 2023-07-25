# Hello 👋

This repository stores my custom Visual Studio Code settings with Vim, includes the 'settings.json' and 'keybindings.json' files, as well as a list of extensions that I use to optimize the development environment.

## 🔌 Extensions

- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

## ⚙️ Configuration options

### VSCode

- `"editor.defaultFormatter"`: set default formatter
- `"editor.fontFamily"`: set the font type for the editor
- `"editor.cursorSurroundingLines"`: sets the number of additional lines to display around the cursor
- `"editor.inlineSuggest.enabled"`: enables inline code hints as you type
- `"editor.suggest.insertMode"`: configures the behavior of code hints when suggested text is inserted.
- `"editor.suggestFontSize"`: sets the font size for code suggestions
- `"editor.guides.bracketPairs"`: displays vertical guides to highlight pairs of brackets
- `"editor.bracketPairColorization.enabled"`: enables colorization of bracket pairs
- `"editor.lineNumbers"`: displays line numbers relative to cursor position
- `"editor.wordWrap"`: turn on automatic line wrapping
- `"editor.detectIndentation"`: turn off automatic indentation detection
- `"typescript.preferences.importModuleSpecifier"`: configures how modules are imported into TypeScript
- `"typescript.updateImportsOnFileMove.enabled"`: enables updating of TypeScript imports when moving files.
- `"editor.tabSize"`: set the tab size
- `"emmet.includeLanguages"`: enables Emmet features for the JavaScript programming language when working on HTML files
- `"files.autoSave"`: set the auto-save option
- `"editor.fontLigatures"`: enable typographic ligatures
- `"editor.rulers"`: disables vertical guides
- `"editor.renderWhitespace"`: hide white space
- `"editor.smoothScrolling"`: enables smooth scrolling
- `"editor.stickyScroll.enabled"`: turn off sticky scrolling
- `"explorer.confirmDelete"`: turn off file deletion confirmation in File Explorer
- `"explorer.confirmDragAndDrop"`: turn off confirmation when dragging and dropping files in File Explorer
- `"editor.guides.indentation"`: turn off indentation guides
- `"editor.linkedEditing"`: enables linked editing, which allows similar symbols to be edited simultaneously
- `"editor.cursorBlinking"`: set the cursor blink style
- `"editor.minimap.enabled"`: disable the minimap
- `"editor.selectionHighlight"`: turn off text selection highlighting
- `"editor.wordSeparators"`: defines the characters that are considered word breakers when making word selections
- `"window.menuBarVisibility"`: set the visibility of the menu bar to appear only when the Alt key is tapped.
- `"workbench.editor.showTabs"`: displays the tabs for open files at the top of the workspace
- `"window.titleBarStyle"`: set the style of the window's title bar
- `"workbench.editor.labelFormat"`: set the label format for tabs in open files
- `"[json]"`: specific settings for JSON files, but do not contain additional settings.
- `"[html]"`: specific configuration for HTML files, using the "vscode.html-language-features" formatter.
- `"window.title"`: sets the title of the window (For example: its name)
- `"workbench.layoutControl.enabled"`: disables controlled layout in the workspace
- `"window.restoreWindows"`: configures how open windows should be restored at startup
- `"window.commandCenter"`: enable the Command Center in the window
- `"symbols.hidesExplorerArrows"`: turn off the expansion arrows in File Explorer

### Vim

- `"vim.foldfix": true`: fixes the bend error when using Ctrl+Shift+[ (Folded) and Ctrl+Shift+] (Unfold)
- `"vim.easymotion": true`: facilitates quick navigation in text
- `"vim.incsearch": true`: highlight search results as you type
- `"vim.useSystemClipboard": true`: allows use of the system clipboard
- `"vim.useCtrlKeys": true`: enables the use of control keys for specific commands
- `"vim.hlsearch": true`: enables search highlighting
- `"vim.normalModeKeyBindingsNonRecursive"`: define key combinations in normal mode

### Prettier

The following three settings are dedicated for JavaScript, TypeScript, and React:

- `"semi"`: indicates that semicolons are not added at the end of sentences
- `"singleQuote"`: use single quotes instead of double quotes for strings
- `"trailingComma"`: do not add commas to the end of lists and objects
- `"htmlWhitespaceSensitivity"`: ignore white spaces in HTML files when formatting them.

> 📝Note: This configuration is only a base and you can modify it to your liking with total freedom. ¡Do not hesitate to experiment and customize it to suit your needs! 💻
