# What's Visual Studio Code

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/64px-Visual_Studio_Code_1.35_icon.svg.png)

Visual Studio Code is a code editor developped by Microsoft in Electron Js, it's open source and used by many developpers

## Extensions

So VSCode have an extension marketplace and here is the list

- AHK++
- Better Comments
- Close HTML/XML tag
- Code Runner
- codeSTACKr Theme
- Composer
- Discloud
- Discord Presence
- Error Lens
- ESLint
- Format HTML in PHP
- Github Copilot
- Github Copilot Chat
- Hex Editor((I don't use it anymore))
- Hex Editor with Tags
- HTML CSS Support
- html tag wrapper
- IntelliPHP - AI Autocomplete for PHP((Appenretly i have this))
- JavaScript (ES6) code snippets
- Live Preview((use the one from microsoft))
- Live Server (Five Server)
- Notepad++ keymap
- npm Intellisense
- Path Intellisense
- PHP
- PHP Profiler
- Pylance
- Python
- Python Debugger
- Remote - SSH
- Remote - SSH: Editing Configuration Files
- Remote Explorer
- Search node_modules
- SFTP
- vscode-icons
- vscode-pdf
- Web Preview
- Web view window
- WSL

## Settings

Here is my settings file, to access it go to settings or press CTRL+, and then press the button to open settings in JSON format and copy and paste my settings

```JSON
{
    /* ================ UI Settings ================ */
    "window.title": "${appName}",
    "editor.bracketPairColorization.enabled": true,
    "explorer.sortOrder": "type",
    "workbench.editor.highlightModifiedTabs": true,
    "workbench.list.smoothScrolling": true,
    "terminal.integrated.defaultProfile.windows": "PowerShell",
    "terminal.integrated.fontFamily": "'Cascadia Code Regular'",
    "terminal.integrated.fontSize": 14,
    "workbench.tree.renderIndentGuides": "none",
    "workbench.tree.indent": 20,
    "css.lint.duplicateProperties": "ignore",
    "git.autofetch": true,
    "emmet.triggerExpansionOnTab": true,
    "editor.renderWhitespace": "selection",
    "editor.tabSize": 2,
    "editor.formatOnSave": false,
    "editor.wordWrap": "on",
    "editor.fontSize": 14,
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.smoothScrolling": true,
    "editor.fontFamily": "'Cascadia Code Regular'",
    "workbench.colorTheme": "codeSTACKr Theme",
    "workbench.iconTheme": "vscode-icons",
    "vsicons.dontShowNewVersionMessage": true,
    "editor.unicodeHighlight.allowedCharacters": {
        "à": true,
        "é": true
    },
    /* ================ Editing Settings ================ */
    "html.format.indentHandlebars": true,
    "html.format.extraLiners": "head, body, /html",
    "workbench.startupEditor": "none",
    "security.workspace.trust.untrustedFiles": "open",
    "hexeditor.columnWidth": 16,
    "hexeditor.showDecodedText": true,
    "hexeditor.defaultEndianness": "little",
    "hexeditor.inspectorType": "aside",
    "editor.unicodeHighlight.invisibleCharacters": false,
    "editor.unicodeHighlight.ambiguousCharacters": false,
    "explorer.confirmDelete": false,
    "editor.stickyScroll.enabled": false,
    "cmake.showOptionsMovedNotification": false,
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 60000,
    "editor.minimap.enabled": false,
    "liveServer.settings.donotVerifyTags": true,
    "python.createEnvironment.trigger": "off",
    "cmake.showConfigureWithDebuggerNotification": false,
    "debug.disassemblyView.showSourceCode": false,
    "python.defaultInterpreterPath": "C:\\Program Files\\Python313\\python.exe",
    "code-runner.clearPreviousOutput": true,
    "code-runner.runInTerminal": true,
    "code-runner.showExecutionMessage": false,
    // "github.copilot.editor.enableAutoCompletions": false,
    "github.copilot.enable": {
        "*": false
    },
    "git.openRepositoryInParentFolders": "never",
    "liveServer.settings.donotShowInfoMsg": true,
    "fiveServer.navigate": true
}
```
