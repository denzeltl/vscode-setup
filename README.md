<div align="center">
<h1>VS Code Setup</h1>
<p>Settings and extensions I use for my VS Code environment.</p>
</div>

## Installation

1. Download **Settings Sync** extension by _Shan Khan_.
2. `Ctrl + Shift + P` and select **Sync: Advanced Options** => **Sync: Download Settings from Public GIST**.
3. Copy and paste gist ID below.

    > Gist ID: 1b81d786e26e2c75d684b61f77ff6d17

4. All settings and extensions will now be applied and downloaded.

---

<details>

<summary><b>Included Extensions</b></summary>

-   **Bracket Pair Colorizer 2** by _CoenraadS_ - A customizable extension for colorizing matching brackets
-   **Cobalt2 Theme Official** by _Wes Bos_ - Official theme by Wes Bos
-   **ES7 React/Redux/GraphQL/React-Native snippets** by _dsznajder_ - Simple extensions for React, Redux and Graphql in JS/TS with ES7 syntax
-   **Git History** by _Don Jayamanne_ - View git log, file history, compare branches or commits
-   **GraphQL** by _GraphQL Foundation_ - GraphQL extension for VSCode adds syntax highlighting, validation, and language features like go to definition, hover information and autocompletion for graphql projects
-   **JavaScript (ES6) code snippets** by _charalampos karypidis_ - Code snippets for JavaScript in ES6 syntax
-   **Material Icon Theme** by _Philipp Kief_ - Material Design Icons for Visual Studio Code
-   **Night Owl** by _sarah.drasner_ - A VS Code theme for the night owls out there
-   **Prettier - Code formatter** by _Prettier_ - Code formatter using prettier
-   **Settings Sync** by _Shan Khan_ - Synchronize Settings, Snippets, Themes, File Icons, Launch, Keybindings, Workspaces and Extensions Across Multiple Machines Using GitHub Gist
-   **SmoothType** by _spikespaz_ - Extension to modify Visual Studio Code to allow for a smooth cursor animation while typing
-   **Todo Tree** by _Gruntfuggly_ - Show TODO, FIXME, etc. comment tags in a tree view
-   **vscode-styled-components** by _Julien Poissonnier_ - Syntax highlighting for styled-components

</details>

---

<details>

<summary><b>settings.json</b></summary>

{
    "workbench.startupEditor": "newUntitledFile",
    "workbench.iconTheme": "material-icon-theme",
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.lineHeight": 29,
    "breadcrumbs.enabled": false,
    "editor.fontSize": 16,
    "editor.cursorWidth": 5,
    "workbench.statusBar.visible": true,
    "workbench.activityBar.visible": true,
    "editor.minimap.renderCharacters": false,
    "editor.minimap.showSlider": "always",
    "workbench.sideBar.location": "left",
    "files.autoSave": "off",
    "editor.renderWhitespace": "none",
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[nunjucks]": {
        "editor.defaultFormatter": "okitavera.vscode-nunjucks-formatter"
    },
    "workbench.colorCustomizations": {
        "editorIndentGuide.activeBackground": "#d1905fdc",
        /* error squiggles */
        "editorError.foreground": "#ff0022",
        // "editorError.border": "#ff0000",
        "editorError.background": "#720505"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "workbench.editor.highlightModifiedTabs": true,
    "php.validate.executablePath": "C:\\xampp\\php\\php.exe",
    "workbench.editor.enablePreview": false,
    "todo-tree.highlights.enabled": true,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "editor.smoothScrolling": true,
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.largeFileOptimizations": false,
    "todo-tree.tree.showScanModeButton": false,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "files.associations": {
        "*.js": "javascriptreact"
    },
    "editor.formatOnPaste": true,
    "git.enableSmartCommit": true,
    "editor.tabSize": 2,
    "prettier.tabWidth": 4,
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.foldingMaximumRegions": 10000,
    "editor.wordWrap": "bounded",
    "editor.wordWrapColumn": 120,
    "prettier.printWidth": 120,
    "git.confirmSync": false,
    "workbench.colorTheme": "Night Owl",
    "editor.fontLigatures": false,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": "active",
    "editor.codeActionsOnSave": {}
}

</details>
