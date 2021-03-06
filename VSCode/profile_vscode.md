

```json
{
    // Python 配置
    "python.pythonPath": "~/venv/bin/python",
    "python.venvPath": "~/venv/",
    "python.linting.pylintEnabled": true,
    "python.linting.pylintPath": "~/venv/bin/pylint",
    // lint使用pep8
    "python.linting.pep8Enabled": false,
    // 如果使用virtualenv的话，可能要指定具体路径
    "python.linting.pep8Path": "~/venv/bin/pycodestyle",
    "python.linting.lintOnSave": true,
    "python.formatting.provider": "yapf",
    "python.formatting.yapfPath": "~/venv/bin/yapf",
    "python.linting.pylintArgs": [
        "--load-plugins",
        "pylint_django",
        "--disable=C,R"
    ],
    //
    // 工作区设置
    "workbench.colorTheme": "Solarized Light",
    "workbench.activityBar.visible": true,
    "workbench.colorCustomizations": {
        "editor.selectionHighlightBackground": "#caf0f3fa",
        "editor.selectionBackground": "#99eafc"
    },
    "workbench.iconTheme": "vscode-icons",
    //
    // 编辑器设置
    "editor.wordWrap": "wordWrapColumn",
    "editor.formatOnType": true,
    "editor.formatOnSave": true,
    "editor.quickSuggestions": {
        "other": true,
        "comments": true,
        "strings": true
    },
    "editor.fontSize": 14,
    "editor.minimap.enabled": true,
    "editor.renderWhitespace": "boundary",
    // 控制编辑器是否应呈现缩进参考线
    "editor.renderIndentGuides": false,
    // 控制编辑器应如何呈现当前行突出显示，可能为“无”、“装订线”、“线”和“全部”。
    // "editor.renderLineHighlight": "all",
    // 控制是否自动隐藏导航线上的折叠控件。
    // "editor.showFoldingControls": "always",
    "editor.roundedSelection": false,
    "editor.rulers": [
        80
    ],
    "editor.minimap.showSlider": "always",
    "editor.wrappingIndent": "indent",
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.snippetSuggestions": "top",
    "editor.formatOnPaste": true,
    // "editor.acceptSuggestionOnEnter": "on",
    //
    // 终端设置
    // 设置后，在终端内右键单击时，这将阻止显示上下文菜单，相反，它将在有选项时进行复制，并且在没有选项时进行粘贴。
    "terminal.integrated.rightClickBehavior": "selectWord",
    "terminal.integrated.fontSize": 13,
    "terminal.external.osxExec": "iterm.app",
    // "terminal.integrated.cursorStyle": "line",
    "terminal.integrated.copyOnSelection": true,
    //
    // 文件设置
    // 配置 glob 模式以排除文件和文件夹。
    "files.exclude": {
        "**/__pycache__": true,
        "**/.idea": true,
        "**/.ipynb_checkpoints": true,
        "**/.gitignore": true,
        "**.pyc": true,
        "**/.github": true,
    },
    "search.exclude": {
        "**/node_modules": true,
        "**/bower_components": true,
        "**/extra_apps": true,
        "**/mxpro/static": true,
        "**/mxpro/media": true,
        "**/mxoline-project/static": true,
        "**/mxoline-project/media": true,
    },
    // 删除多余空格
    "files.trimTrailingWhitespace": true,
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "explorer.confirmDragAndDrop": false,
    "debug.internalConsoleOptions": "openOnSessionStart",
    "debug.openExplorerOnEnd": true,
    //
    // 其他设置
    "telemetry.enableCrashReporter": false,
    "telemetry.enableTelemetry": false,
    //
    // 插件设置
    "sync.gist": "21b33ccd186475771f3c20ca77d38768",
    "sync.lastUpload": "2018-05-13T14:38:06.365Z",
    "sync.autoDownload": false,
    "sync.autoUpload": true,
    "sync.lastDownload": "2018-03-31T04:47:51.045Z",
    "sync.forceDownload": false,
    "sync.host": "",
    "sync.pathPrefix": "",
    "sync.quietSync": true,
    "sync.askGistName": false,
    "vsicons.dontShowNewVersionMessage": true,
    "workbench.panel.defaultLocation": "bottom",
    "explorer.confirmDelete": false,
    "git.confirmSync": false,
    "workbench.startupEditor": "newUntitledFile",
    "sync.removeExtensions": true,
    "sync.syncExtensions": true,
    "gitlens.advanced.messages": {
        "suppressCommitHasNoPreviousCommitWarning": false,
        "suppressCommitNotFoundWarning": false,
        "suppressFileNotUnderSourceControlWarning": false,
        "suppressGitVersionWarning": false,
        "suppressLineUncommittedWarning": false,
        "suppressNoRepositoryWarning": false,
        "suppressResultsExplorerNotice": false,
        "suppressShowKeyBindingsNotice": true
    },
    "gitlens.defaultDateStyle": "absolute",
    "gitlens.defaultDateFormat": "YY-MM-DD HH:mm:ss",
    "gitlens.statusBar.alignment": "left",
    "search.location": "sidebar",
    "files.encoding": "utf8",
    "editor.showFoldingControls": "always",
    "editor.find.seedSearchStringFromSelection": true,
    "window.openFilesInNewWindow": "off",
    "editor.scrollBeyondLastLine": true,
    "gitlens.historyExplorer.enabled": true,
}

```

