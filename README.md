# FAR
Fix (NieR) Automata Resolution

## PSA: Incompatibility with the latest versions of the game!

This is the original version of FAR, developed back in 2017 for the original Steam version of the game. Since then the Steam version have being extensively updated in 2021, with the game releasing on the Microsoft Store as well. The versions listed here is not compatible with those updated copies of the game, and requires an original 2017 version of the game to function.

* If you want to use FAR with an updated copy of the game, please see [the official Special K wiki](https://wiki.special-k.info/SpecialK/Custom/FAR) for instructions on how to install an updated copy of FAR for those versions.

* If you want to downgrade your Steam copy to the 2017 version, you can do so by following [the downgrade instructions](https://www.nexusmods.com/nierautomata/articles/7) provided by the LodMod creator over on Nexus.

---

## What follows below is the original readme file for the 2017 version of FAR: 

* [Latest stable release](https://github.com/Kaldaien/FAR/releases/latest)
* [All releases](https://github.com/Kaldaien/FAR/releases)

For help and/or questions, please post in the [FAR thread](http://steamcommunity.com/groups/SpecialK_Mods/discussions/3/1334600128973500691/) over on the Steam discussion boards.

For more instructions and guides on how to use FAR, see this [Tweak Guide](http://steamcommunity.com/sharedfiles/filedetails/?id=914437196) over on the Steam guides for NieR:Automata.


## Main Features

* Fixes native fullscreen resolution
* Allows adjusting **Global Illumination** for a performance boost.
* Allows adjusting the resolution of **Bloom** and **Ambient Occlusion** effects to the current framebuffer resolution.
* Includes a freecam look.
* Includes a framerate unlocker.


## Framerate Unlocker
The framerate unlocker is known to **break** cutscenes and scripting in the game. **Use at your own risk!**

Steps to enable the framerate unlocker:

1. Disable V-Sync in-game
2. Disable the built-in frame limiter of FAR (set it to 0)
3. Enable **Remove 60 FPS Cap**
4. *(optional)* Edit ```RefreshRate=-1``` in dxgi.ini to override the default 60 Hz refresh rate of the game.


## Keybindings
### Basics
Keybinding | Function
---------- | ----------
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd> | Toggle On Screen Display (OSD)
Keyboard: <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Backspace</kbd><br>Gamepad: <kbd>Back</kbd>/<kbd>Select</kbd> + <kbd>Start</kbd> | Toggle Config Menu
Hold <kbd>Ctrl</kbd> + <kbd>Shift</kbd> while launching the game | Opens the Injection Compatibility Options

### Framerate Unlocker
Keybinding | Function
---------- | ----------
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>.</kbd> | Toggle 60 FPS cap

### Camera and HUD
*Keybindings can be changed in the control panel of FAR. Some non-English keyboard users might need to rebind the keys before they work.*

Keybinding | Function
---------- | ----------
<kbd>Numpad 5</kbd> | Turn on/off freelook (will disable XInput movement control)
<kbd>Numpad /</kbd> | Lock Camera Origin
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>F11</kbd> | Lock Camera Focus
<kbd>Numpad -</kbd> | HUD Free Screenshots

### Config Menu
Keybinding | Function
---------- | ----------
Keyboard: <kbd>Caps Lock</kbd><br>Gamepad: Hold <kbd>Back</kbd>/<kbd>Select</kbd> for 0.5 seconds | Toggle Exclusive Input Mode (game vs. config menu)
Keyboard: <kbd>↑</kbd>/<kbd>↓</kbd>/<kbd>←</kbd>/<kbd>→</kbd><br>Gamepad: <kbd>D-pad</kbd> | Cycle Through UI Items
Keyboard: <kbd>Enter</kbd><br>Gamepad: <kbd>A</kbd>/<kbd>×</kbd> | Activate Selected Item
Keyboard: <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Backspace</kbd><br>Gamepad: <kbd>B</kbd>/<kbd>○</kbd> | Exit Config Menu
Exclusive Keyboard Mode: <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>↑</kbd>/<kbd>↓</kbd>/<kbd>←</kbd>/<kbd>→</kbd><br>Gamepad: <kbd>X</kbd>/<kbd>□</kbd> + <kbd>Left Analog Stick</kbd> | Move the Control Panel

### On-Screen Display (OSD)
*Color and scale config is stored in **Documents\My Mods\SpecialK\Global\osd.ini***

Keybinding | Function
---------- | ----------
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd> | Toggle On Screen Display (OSD)
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>+</kbd>/<kbd>-</kbd> | Resize OSD
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd> | Toggle Framerate Counter
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>T</kbd> | Toggle Clock / Version
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>G</kbd> | Toggle GPU Monitor
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd> | Toggle CPU Monitor
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>M</kbd> | Toggle Memory Monitor
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd> | Toggle I/O Monitor
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>D</kbd> | Toggle Disk Monitor
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> | Toggle Page File Monitor
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd> | Toggle D3D11 Shader Analytics

### Advanced
Keybinding | Function   | Usage
---------- | ---------- | ---------- 
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Tab</kbd> | Command Console | See [documentation](https://gist.github.com/Kaldaien/185506559f2cbe6d4415d15b2e05fe78) for commands 


# Credits

* DrDaxxy for fullscreen resolution fix and global illumination tweak.
* Durante for ambient occlusion and bloom resolution tweak.
* Francesco149 for framerate unlocker.
* IDK31 and Smithfield for freecam look.
* GitHub contributors


# Source Code for Special K
The source code for Special K is hosted over on [GitLab](https://gitlab.com/Kaldaien/SpecialK/).
