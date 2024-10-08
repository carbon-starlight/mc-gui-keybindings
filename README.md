# Use keybindings you are used to in any terminal
 Configure your Midnight Commander and MCEdit to use GUI-standard (like in Micro or VSCode) keybindings

![image](https://github.com/user-attachments/assets/610fa755-ee14-48cc-96c3-8590eec524ee)

With advanced mouse support and drop-down menus I always considered MC and MCEdit a great choice for terminal beginners. The only thing that could (and did) complicate their experience
 are unintuitive default keybinding choices. The configurations you will find here will allow you to use your midnight commander file browser and editor with the same shortcuts 
 you are probably used to in modern GUI applications

Warning: only MCEdit keybindings are avalible yet. The project right now is being actively developed, please, feel free to contribute!

## Installation


Run the following command in your terminal:

* **Shortcuts from Nautilus file manager and VSCode text editor:**

_For UNIX-like systems (Linux, BSDs, Haiku and MacOS):_

```
cd ~/.config/mc && curl -o mc.keymap https://raw.githubusercontent.com/carbon-starlight/mc-gui-keybindings/main/nautilus-vscode/mc.keymap
```
_For Windows (using PowerShell):_

```
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/carbon-starlight/mc-gui-keybindings/main/nautilus-vscode/mc.keymap" -OutFile "C:\Program Files (x86)\Midnight Commander\etc\mc.default.keymap"
```

## Copying

Same license as in standard MC: GPLv3-or-later.

## Misc

I also recommend using the [Extend layer](https://dreymar.colemak.org/layers-extend.html) and some [symbol layer](https://colemakmods.github.io/ergonomic-mods/symbols.html) for the best typing experience.
