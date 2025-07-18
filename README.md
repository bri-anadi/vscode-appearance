# 230201-VSCode-Appearance.
Visual Studio Code Appearance.

---
## Friday, 18 July 2025
> settings.json
```json
{
    "editor.copyWithSyntaxHighlighting": false,
    "diffEditor.ignoreTrimWhitespace": false,
    "workbench.editor.enablePreview": false,
    "window.newWindowDimensions": "inherit",
    "files.trimTrailingWhitespace": true,
    "diffEditor.renderSideBySide": false,
    "editor.snippetSuggestions": "top",
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "workbench.editor.showTabs": "single",
    "editor.minimap.enabled": false,
    "editor.lineNumbers": "on",
    "scm.diffDecorations": "none",
    "editor.hover.enabled": false,
    "editor.matchBrackets": "near",
    "workbench.tips.enabled": false,
    "git.decorations.enabled": false,
    "workbench.startupEditor": "none",
    "editor.lightbulb.enabled": "off",
    "editor.selectionHighlight": false,
    "editor.overviewRulerBorder": false,
    "editor.renderLineHighlight": "none",
    "editor.occurrencesHighlight": "off",
    "problems.decorations.enabled": false,
    "editor.renderControlCharacters": false,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "files.autoSave": "afterDelay",
    "editor.fontSize": 18,
    "editor.lineHeight": 48,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Palenight Operator",
    "terminal.integrated.lineHeight": 1.8,
    "editor.guides.indentation": false,
    "editor.linkedEditing": true,
    "diffEditor.wordWrap": "off",
    "git.verboseCommit": true,
    "workbench.settings.applyToAllProfiles": [
        "prettier.printWidth"
    ],
    "workbench.activityBar.location": "hidden",
    "launch": {
        "configurations": [],
        "compounds": []
    },
    "editor.codeActionsOnSave": {},
    "window.menuBarVisibility": "compact",
    "[python]": {
        "editor.defaultFormatter": "ms-python.autopep8"
    },
    "editor.rulers": [],
    "workbench.colorCustomizations": {},
    "json.schemas": [],
    "dart.lineLength": 150,
    "[dart]": {
        "editor.tabSize": 2,
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.selectionHighlight": false,
        "editor.suggestSelection": "first",
        "editor.tabCompletion": "onlySnippets",
        "editor.wordBasedSuggestions": "allDocuments",
        "editor.rulers": [
            850
        ]
    },
    "problems.defaultViewMode": "table",
    "problems.showCurrentInStatus": true,
    "security.workspace.trust.untrustedFiles": "open",
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "git.enableSmartCommit": true,
    "[javascript]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "editor.emptySelectionClipboard": false,
    "editor.hideCursorInOverviewRuler": true,
    "editor.stickyScroll.scrollWithEditor": false,
    "workbench.tree.enableStickyScroll": false,
    "editor.stickyScroll.enabled": false,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.defaultFormatter": "bradlc.vscode-tailwindcss",
    "liveServer.settings.donotVerifyTags": true,
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[postcss]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "emmet.includeLanguages": {
        "postcss": "css"
    },
    "files.associations": {
        "*.css": "tailwindcss",
        "*.php": "php"
    },
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "prettier.printWidth": 1600,
    "debug.javascript.autoAttachFilter": "always",
    "[tailwindcss]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "tailwindCSS.includeLanguages": {
        "html": "html",
        "javascript": "javascript",
        "css": "css",
        "blade": "html",
        "php": "html"
    },
    "editor.quickSuggestions": {
        "strings": true
    },
    "[blade]": {
        "editor.defaultFormatter": "shufo.vscode-blade-formatter"
    },
    "bladeFormatter.format.wrapLineLength": 800,
    "editor.fontLigatures": true,
    "tailwindCSS.emmetCompletions": true,
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
    "intelephense.diagnostics.undefinedProperties": false,
    "solidity.telemetry": false,
    "[solidity]": {
        "editor.defaultFormatter": "NomicFoundation.hardhat-solidity",
        "editor.wordWrap": "off",
    },
    "solidity.remappings": [
        "forge-std/=lib/forge-std/src/",
        "openzeppelin/=lib/openzeppelin-contracts/"
    ],
    "solidity.formatter": "forge",
    "[typescriptreact]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "[typescript]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "solidity.packageDefaultDependenciesContractsDirectory": "contracts",
    "solidity.packageDefaultDependenciesDirectory": "node_modules",
    "liveServer.settings.donotShowInfoMsg": true,
    "editor.formatOnSave": true,
    "editor.unicodeHighlight.ambiguousCharacters": false,
    "editor.fontFamily": "Maple Mono Thin",
    "editor.guides.bracketPairsHorizontal": false,
    "editor.guides.highlightActiveBracketPair": false,
    "github.copilot.nextEditSuggestions.enabled": false,
    "github.copilot.enable": {
        "*": false,
        "plaintext": false,
        "markdown": false,
        "scminput": false,
        "solidity": false
    },
    "cursor.cpp.disabledLanguages": [
        "plaintext",
        "markdown",
        "scminput",
        "solidity"
    ],
    "python.analysis.packageIndexDepths": [
        {
            "name": "sklearn",
            "depth": 2
        },
        {
            "name": "matplotlib",
            "depth": 2
        },
        {
            "name": "scipy",
            "depth": 2
        },
        {
            "name": "django",
            "depth": 2
        },
        {
            "name": "flask",
            "depth": 2
        },
        {
            "name": "fastapi",
            "depth": 2
        }
    ],
    "[prisma]": {
        "editor.defaultFormatter": "Prisma.prisma"
    },
    "evenBetterToml.formatter.columnWidth": 800
}
```


## Tuesday, 28 February 2023
![https://github.com/bri-anadi/vscode-appearance/blob/main/vscode-appearance-2.png?raw=true](https://github.com/bri-anadi/vscode-appearance/blob/main/vscode-appearance-2.png?raw=true)

> setting.json
```json
{
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "none",
    "workbench.activityBar.visible": false,
    "workbench.statusBar.visible": false,
    "window.menuBarVisibility": "compact",
    "files.autoSave": "afterDelay",
    "editor.fontFamily": "Cascadia Code Light",
    "editor.fontSize": 20,
    "editor.lineHeight": 76,
    "editor.fontLigatures": true,
    "breadcrumbs.enabled": false,
    "editor.lineNumbers": "off",
    "editor.matchBrackets": "near",
    "editor.minimap.enabled": false,
    "editor.lightbulb.enabled": false,
    "editor.overviewRulerBorder": false,
    "editor.selectionHighlight": false,
    "editor.renderLineHighlight": "none",
    "editor.occurrencesHighlight": false,
    "workbench.colorTheme": "Palenight Operator",
    "workbench.editor.showTabs": false,
    "editor.detectIndentation": false,
    "editor.wordWrap": "off",
    "editor.trimAutoWhitespace": false,
    "editor.renderWhitespace": "none",
    "editor.guides.indentation": false,
    "terminal.integrated.lineHeight": 2,
    "emmet.triggerExpansionOnTab": true,
    "workbench.layoutControl.enabled": false,
    "git.openRepositoryInParentFolders": "never",
    "emmet.includeLanguages": {
        "blade": "html"
    },
}
```

### Style Extensions
1. Palenight Theme // [https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme)
2. Material Icons Theme // [https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) 

</br>

---

## Wednesday, 01 February 2023

![https://github.com/bri-anadi/vscode-appearance/blob/main/vscode-appearance.png?raw=true](https://github.com/bri-anadi/vscode-appearance/blob/main/vscode-appearance.png?raw=true)

> setting.json
```json
{
  "editor.copyWithSyntaxHighlighting": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.emptySelectionClipboard": false,
  "workbench.editor.enablePreview": false,
  "window.newWindowDimensions": "inherit",
  "editor.multiCursorModifier": "ctrlCmd",
  "files.trimTrailingWhitespace": true,
  "diffEditor.renderSideBySide": false,
  "editor.snippetSuggestions": "top",
  "editor.detectIndentation": false,
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "workbench.activityBar.visible": false,
  "workbench.statusBar.visible": false,
  "workbench.editor.showTabs": false,
  "editor.minimap.enabled": false,
  "editor.lineNumbers": "off",
  "breadcrumbs.enabled": false,
  "scm.diffDecorations": "none",
  "editor.hover.enabled": false,
  "editor.matchBrackets": "never",
  "workbench.tips.enabled": false,
  "editor.colorDecorators": false,
  "git.decorations.enabled": false,
  "workbench.startupEditor": "none",
  "editor.lightbulb.enabled": false,
  "editor.selectionHighlight": false,
  "editor.overviewRulerBorder": false,
  "editor.renderLineHighlight": "none",
  "editor.occurrencesHighlight": false,
  "problems.decorations.enabled": false,
  "editor.renderControlCharacters": false,
  "editor.hideCursorInOverviewRuler": true,
  "editor.gotoLocation.multipleReferences": "goto",
  "editor.gotoLocation.multipleDefinitions": "goto",
  "editor.gotoLocation.multipleDeclarations": "goto",
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "editor.gotoLocation.multipleImplementations": "goto",
  "editor.gotoLocation.multipleTypeDefinitions": "goto",
  "window.menuBarVisibility": "compact",
  "workbench.layoutControl.enabled": false,
  "files.autoSave": "afterDelay",
  "editor.fontSize": 16,
  "editor.fontFamily": "Cascadia Code Light",
  "editor.lineHeight": 54,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Parsinta Exclusive",
  "terminal.integrated.lineHeight": 1.8,
  "editor.guides.indentation": false,
  "editor.linkedEditing": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "diffEditor.wordWrap": "off",
}
```

### Style Extensions
1. Parsinta Exclusive // [https://marketplace.visualstudio.com/items?itemName=Parsinta.parsinta-exclusive](https://marketplace.visualstudio.com/items?itemName=Parsinta.parsinta-exclusive)
2. Material Icons Theme // [https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) 

### Releated Links
1. Article: Vscode: Clean and Minimalistic // [https://parsinta.com/articles/vscode-wri2ux](https://parsinta.com/articles/vscode-wri2ux)
2. Youtube: Vscode Parsinta // [https://youtu.be/RV8u9y0zEr0](https://youtu.be/RV8u9y0zEr0)
