# 常用的extensions

```
$ code --list-extensions                                                                                                                                                                                                           [11:59:22]
akamud.vscode-theme-onedark
austin.code-gnu-global
DavidAnson.vscode-markdownlint
DevonDCarew.bazel-code
donjayamanne.githistory
DotJoshJohnson.xml
eamodio.gitlens
faustinoaq.lex-flex-yacc-bison
James-Yu.latex-workshop
josephtbradley.hive-sql
maelvalais.autoconf
matthewferreira.cppcheck
mine.cpplint
ms-azuretools.vscode-docker
ms-python.python
ms-vscode-remote.remote-ssh
ms-vscode-remote.remote-ssh-edit
ms-vscode-remote.remote-wsl
ms-vscode-remote.vscode-remote-extensionpack
ms-vscode.cmake-tools
ms-vscode.cpptools
peterj.proto
rafaelmaiolla.remote-vscode
redhat.java
ryu1kn.partial-diff
sidneys1.gitconfig
yzane.markdown-pdf
```

# 常用的个性配置

```
{
    "editor.minimap.enabled": false,
    "workbench.statusBar.visible": true,
    "editor.wordWrap": "on",
    "gitlens.advanced.messages": {
        "suppressShowKeyBindingsNotice": true
    },
    "gitlens.historyExplorer.enabled": true,
    "window.title": "${activeEditorLong}${separator}${rootName}",
    "workbench.activityBar.visible": true,
    "workbench.startupEditor": "newUntitledFile",
    "files.encoding": "utf8",
    "files.autoGuessEncoding":true,
    "editor.tabSize": 4,
    "editor.insertSpaces": true,
    "workbench.colorTheme": "Atom One Dark",
    "gitlens.views.fileHistory.enabled": true,
    "gitlens.views.lineHistory.enabled": true,
    "workbench.colorCustomizations": {
        "editor.selectionBackground": "#135564",
        "editor.selectionHighlightBackground": "#135564",
        "terminal.foreground" : "#959b9771",
        "terminal.background" : "#030303"
    },
    "window.zoomLevel": 0,
    "remote.onstartup": true,
    "workbench.statusBar.feedback.visible": false,
    "breadcrumbs.enabled": true,
    "remote.SSH.showLoginTerminal": true,
    
}
```

# 通过命令行打开常用工程
1. "code" command
https://stackoverflow.com/questions/29971053/how-to-open-visual-studio-code-from-the-command-line-on-osx

2. Shortcut command
/usr/local/bin/code ~/lu-personal-file/lu-github/

3. 怎么命令行打开SSH远程的项目，目前还没找到方法
有人提问但还没人回答： https://stackoverflow.com/questions/59904857/how-to-invoke-vscode-in-ssh-mode-from-the-command-line
