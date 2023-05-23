# vscode-vim-settings

### Apart from below settings i also change in VS Code keyboard mappings:
From      |To     |
----------|-------|
Alt + UP  |Alt + k|
Alt + Down|Alt + j|

```javascript
{
	"terminal.integrated.enableMultiLinePasteWarning": false,
	"git.autofetch": true,
	"git.enableSmartCommit": true,
	"explorer.confirmDelete": false,
	"explorer.confirmDragAndDrop": false,

	// Workbench
	"workbench.colorTheme": "Default Dark+",
	//Allow tabs to shrink when there is not enough space available to display all tabs at the same time.
	"workbench.editor.tabSizing": "shrink",
	"workbench.activityBar.visible": true,
	"workbench.startupEditor": "newUntitledFile",
	"diffEditor.wordWrap": "on",

    //Appearance
	"editor.cursorBlinking": "expand",
    "editor.bracketPairColorization.enabled": false,
	"editor.glyphMargin": false,
	"editor.wordWrap": "on",

	//Format
	"editor.formatOnSave": true,
	"editor.autoClosingBrackets": "never",
	"editor.formatOnPaste": true,
	"prettier.useTabs": true,
	"prettier.singleQuote": true,
	"prettier.arrowParens": "avoid",
	"prettier.trailingComma": "none",
	"prettier.jsxSingleQuote": true,
	"editor.formatOnSaveMode": "modificationsIfAvailable",

	//Vim
	"vim.useCtrlKeys": true,
	"vim.useSystemClipboard": true,
	"vim.insertModeKeyBindings": [
		{
			"before": ["j", "j"],
			"after": ["<Esc>"]
		}
	],
	"vim.visualModeKeyBindings": [
		{
			"before": ["i"],
			"after": ["<Esc>", "i"]
		}
	],
	"vim.handleKeys": {
		"<C-a>": false,
		"<C-f>": false,
		"<C-d>": false,
		"<C-c>": false,
		"<C-x>": false,
		"<C-v>": false
	},

	//JS & TS
	"javascript.suggestionActions.enabled": false,
	"typescript.suggestionActions.enabled": false,
	"javascript.updateImportsOnFileMove.enabled": "always",
	"typescript.updateImportsOnFileMove.enabled": "always",

	//Terminal
	"terminal.integrated.fontSize": 14,
	"terminal.integrated.tabs.enabled": false,
	// "window.zoomLevel": 1
}

```
