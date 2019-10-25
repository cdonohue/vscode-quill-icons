<img align="left" width="80" height="80" src="https://github.com/cdonohue/vscode-quill-icons/raw/master/icons/quill_light@2x.png" alt="Quill Icons Logo">

# Quill Icons

A light/dark low contrast file icon set for VSCode that borrows from and extends [Feather Icons](https://feathericons.com). A minimal icon theme is also included that only differentiates files and folders.

### Screenshots

#### Full icon theme

![dark](https://github.com/cdonohue/vscode-quill-icons/raw/master/screenshots/demo-dark.png)

![light](https://github.com/cdonohue/vscode-quill-icons/raw/master/screenshots/demo-light.png)

#### Minimal icon theme

![dark-minimal](https://github.com/cdonohue/vscode-quill-icons/raw/master/screenshots/demo-dark-minimal.png)

![light-minimal](https://github.com/cdonohue/vscode-quill-icons/raw/master/screenshots/demo-light-minimal.png)

### Icon reference

| Name            | Icon                                           | Purpose                                                                                                              |
| --------------- | ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Folder          | ![folder](icons/folder_light@2x.png)           | Collapsed Folders                                                                                                    |
| Folder (Open)   | ![open-folder](icons/folder-open_light@2x.png) | Expanded Folders                                                                                                     |
| File            | ![file](icons/file_light@2x.png)               | Fallback for files not decorated by another icon. In the minimal theme, it represents anything that is not a folder. |
| Settings        | ![settings](icons/settings_light@2x.png)       | `package.json` and other configuration-related files                                                                 |
| Prettier        | ![prettier](icons/prettier_light@2x.png)       | `.prettierrc`                                                                                                        |
| ESLint          | ![eslint](icons/eslint_light@2x.png)           | `eslint` configurations                                                                                              |
| Code            | ![code](icons/code_light@2x.png)               | Source code files (`.js`, `.py`, etc)                                                                                |
| Markup          | ![markup](icons/html_light@2x.png)             | `.html`, `.xml`, etc                                                                                                 |
| Hash            | ![hash](icons/hash_light@2x.png)               | CSS related files (`.css`, `.scss`, etc)                                                                             |
| Book            | ![book](icons/book_light@2x.png)               | `.md` and other documentation files                                                                                  |
| Package/Archive | ![package](icons/package_light@2x.png)         | Package/archive files                                                                                                |
| Image           | ![image](icons/image_light@2x.png)             | Images (`.svg`, `.png`, etc)                                                                                         |
| Camera          | ![camera](icons/camera_light@2x.png)           | Snapshots (`.snap`)                                                                                                  |
| Database        | ![database](icons/database_light@2x.png)       | Data files (`.json`, `.sql`)                                                                                         |
| Terminal        | ![terminal](icons/terminal_light@2x.png)       | `.zshrc`, `.bashrc`                                                                                                  |
| Lock            | ![lock](icons/lock_light@2x.png)               | `.lock`                                                                                                              |
| Info            | ![info](icons/info_light@2x.png)               | Log files                                                                                                            |
| Git             | ![git](icons/git_light@2x.png)                 | Git-related files (`.gitignore`)                         |

### Themes shown
The `dark` theme shown above is [Subliminal Next](https://marketplace.visualstudio.com/items?itemName=konradkeska.subliminal-next) with custom overrides:
```json
{
  "workbench.colorCustomizations": {
    "[Subliminal Next]": {
      "editor.lineHighlightBackground": "#272c35",
      "editorGroupHeader.tabsBackground": "#232830",
      "editorGroupHeader.tabsBorder": "#1e2229",
      "editorGutter.addedBackground": "#77b386",
      "editorGutter.modifiedBackground": "#70aaab",
      "editorIndentGuide.activeBackground": "#ffffff11",
      "editorIndentGuide.background": "#ffffff08",
      "editorLineNumber.activeForeground": "#5a677c",
      "editorLineNumber.foreground": "#38404d",
      "editorLink.activeForeground": "#74B9E9",
      "scrollbar.shadow": "#0000",
      "sideBar.background": "#1c2026",
      "sideBar.border": "#0000",
      "sideBarSectionHeader.background": "#21252c",
      "statusBar.background": "#1F242B",
      "statusBar.border": "#1C2026",
      "statusBar.foreground": "#454f5f",
      "tab.activeBackground": "#0000",
      "tab.border": "#0000",
      "tab.inactiveBackground": "#0000",
      "textLink.activeForeground": "#A9D9F6",
      "textLink.foreground": "#74B9E9",
      "titleBar.border": "#0000",
      "tree.indentGuidesStroke": "#fff1",
      "widget.shadow": "#0005"
    },
  }
}
```

The `light` theme shown is [Ayu Light](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu) with custom overrides:
```json
{
  "workbench.colorCustomizations": {
    "[Ayu Light]": {
      "badge.background": "#55b4d4",
      "editorGroupHeader.tabsBorder": "#eef0f1",
      "editorIndentGuide.activeBackground": "#0002",
      "editorIndentGuide.background": "#0001",
      "gitDecoration.modifiedResourceForeground": "#55b4d4",
      "gitDecoration.untrackedResourceForeground": "#96b663",
      "list.activeSelectionBackground": "#cdd1d6",
      "list.activeSelectionForeground": "#616a75",
      "list.focusForeground": "#616a75",
      "list.highlightForeground": "#55b4d4",
      "list.hoverForeground": "#616a75",
      "list.inactiveSelectionForeground": "#616a75",
      "list.warningForeground": "#fa8d3e",
      "sideBar.background": "#e3e6e8",
      "sideBar.border": "#0000",
      "sideBar.foreground": "#7f8994",      
      "sideBarSectionHeader.background": "#d8dcdf",     
      "statusBar.background": "#cdd1d6",
      "statusBar.border": "#0000",
      "statusBar.foreground": "#7f8994",
      "tab.inactiveForeground": "#c5c9ce",
      "terminal.ansiBlack": "#144252",
      "terminal.ansiBlue": "#addbeb",
      "terminal.ansiCyan": "#2985a3",
      "terminal.ansiGreen": "#5cb8d6",
      "terminal.ansiWhite": "#eff8fb",
      "terminal.background": "#0a2129",
      "terminal.foreground": "#ceeaf3",
      "titleBar.activeBackground": "#cdd1d6",
      "titleBar.activeForeground": "#7f8994",
      "titleBar.border": "#0000",
      "tree.indentGuidesStroke": "#0001",
    },
  }
}
```

The title bar is hidden by using the [Customize UI extension](https://marketplace.visualstudio.com/items?itemName=iocave.customize-ui) 

## Credits

Many thanks to [@colebemis](https://github.com/colebemis) and [@feathericons](https://github.com/feathericons) for inspiration.

## License

MIT License 2019 © Chad Donohue
