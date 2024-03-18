# Procedural Dungeon Example

[![Plugin version number](https://img.shields.io/badge/Plugin_Version-3.1-blue)][1]
![Unreal Engine Supported Versions](https://img.shields.io/badge/Unreal_Engine-5.2_|_5.3-9455CE?logo=unrealengine)
[![License](https://img.shields.io/github/license/BenPyton/DungeonExample?label=License&color=blue)](LICENSE)
[![Actively Maintained](https://img.shields.io/badge/Maintenance%20Level-Actively%20Maintained-green.svg)](https://gist.github.com/cheerfulstoic/d107229326a01ff0f333a1d3476e068d)

${\color{orange}\boxed{DISCLAIMER}}$ This is still a Work in Progress, some behaviors may not be implemented correctly yet.

This is an example project for my [Procedural Dungeon plugin][1].

This project uses version 3.1 of the plugin.\
You can upgrade to a newer plugin version but be careful when downgrading to an older plugin version, as some features may be missing.

This is a blueprint-only project but you can turn it as a C++ project if you like to.

You can also upgrade the targeted Unreal Engine version (by right-clicking on the `.uproject`), but you will **not** be able to downgrade to UE 5.1 or older.

If you have any issue, a bug or a crash, you can open an issue ticket in this repo.\
If you want help or ask questions about this example project or the plugin, you can join the [Discord server](https://discord.gg/YE2dPda2CC) dedicated to them.

## Installation

Download (or clone) this project anywhere you want.\
On Windows, install the pre-compiled binary of the [Procedural Dungeon plugin][1] either way you like:
- In the engine's `Plugins` folder
- In your newly downloaded project's `Plugins` folder

Then you can launch it by double-clicking the `.uproject` file.

Alternatively on Windows (or mandatory for other platforms), you can turn it into a C++ project by creating a C++ class from the editor, and download plugin's source code and place it in the `Plugins` folder of the project to compile it with the project.

## How to Use

Once you have opened the editor, you will have the `Main Menu` map opened and you will see nothing but the black void of a lightless universe.\
If you run in the editor, a simple main menu will be displayed and you have to hit play to load the `Master Level` map.\
Once there, you will have the controls displayed on the screen. Hit `enter` to generate a dungeon.

Alternatively, in the editor, you can set 2 or more players and launch in standalone mode (like described [here](https://github.com/BenPyton/ProceduralDungeon/wiki/Multiplayer#multiplayer-in-editor)) to try out the multiplayer.\
Once in the `Main Menu` map, first click on the `Host` button on one of them, and `Join` on the others (keep `127.0.0.1` as the ip address for a local testing).\
The clients will join the host and you will be able to test the multiplayer.

## License

This project is under [Creative Common 0 license](LICENSE).  
![CC0-License](https://licensebuttons.net/p/zero/1.0/88x31.png)

## *Support Me*

If you like my plugin and/or this example project, please consider tipping:

[![Ko-fi](https://img.shields.io/badge/Ko--fi-ff5f5f?style=for-the-badge)](https://ko-fi.com/M4M3NW2JV)
[![liberapay](https://img.shields.io/badge/liberapay-f6c915?style=for-the-badge)](https://liberapay.com/BenPyton/donate)
[![PayPal](https://img.shields.io/badge/PayPal-142c8e?style=for-the-badge)](https://www.paypal.com/donate/?hosted_button_id=9VWP66JU5DZXN)


[1]: https://github.com/BenPyton/ProceduralDungeon
