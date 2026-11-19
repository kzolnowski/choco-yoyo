# choco-yoyo

## Installation

Because theme is not published to VSCode marketplace yet you have to install theme manually. Just copy this folder to ~/.vscode/extensions/ and you good to go.

**Enjoy!**

## Active editor tab color in VS Code 1.146+

VS Code's modern UI uses "connected" editor tabs by default (`workbench.experimental.modernUIEditorTabStyle`).
In that style the active tab background is taken only from user `workbench.colorCustomizations`,
and the tab colors defined in this theme are ignored. To get the lighter active tab, add this to your `settings.json`:

```jsonc
"workbench.colorCustomizations": {
    "[Choco by yOyO-]": {
        "modernEditorTab.activeBackground": "#5A4335",
        "modernEditorTab.activeHoverBackground": "#654C3C"
    }
}
```

The theme colors apply as is with the classic tabs or the "pill" tab style.
