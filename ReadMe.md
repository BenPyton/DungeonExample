# Procedural Dungeon Example

[![Plugin version number](https://img.shields.io/badge/Plugin_Version-3.7-blue)][1]
![Unreal Engine Supported Versions](https://img.shields.io/badge/Unreal_Engine-5.5+-9455CE?logo=unrealengine)
[![License](https://img.shields.io/github/license/BenPyton/DungeonExample?label=License&color=blue)](LICENSE)
[![Actively Maintained](https://img.shields.io/badge/Maintenance%20Level-Actively%20Maintained-green.svg)](https://gist.github.com/cheerfulstoic/d107229326a01ff0f333a1d3476e068d)

> [!WARNING]
> This is still a Work in Progress, some features of the plugin may not be implemented yet.

This is an example project for my [Procedural Dungeon plugin][1].

This project uses version 3.7 of the plugin.\
You can upgrade to a **newer plugin** version but be careful when downgrading to an older plugin version, as some features may be missing.

This is a blueprint-only project but you can turn it as a C++ project if you like to.

You can also **upgrade** the targeted Unreal Engine version (by right-clicking on the `.uproject`), but you should **not** downgrade to UE older versions.

If you have any issue, a bug or a crash, you can open an issue ticket in this repo.\
If you want help or ask questions about this example project or the plugin, you can join the [Discord server](https://discord.gg/YE2dPda2CC) dedicated to them.

## Installation

1. Download (or clone) this project anywhere you want.

2. Follow the [installation instructions](https://benpyton.github.io/ProceduralDungeon/guides/Getting-Started/Installation) of the Procedural Dungeon plugin.

3. Then you can launch it by double-clicking the `.uproject` file.

## How to Use

### Single player

Once you have opened the editor, you will have the `Main Menu` map opened and you will see nothing but the black void of a lightless universe.

If you run in the editor, a simple main menu will be displayed and you have to hit the button `Solo` to load the `Master Level` map.

Once there, you will have the controls displayed on the screen. Hit `enter` to generate a dungeon.

### Multiplayer

In the editor, you can set 2 or more players and launch in standalone mode (like described [here](https://benpyton.github.io/ProceduralDungeon/guides/Misc/Multiplayer)) to try out the multiplayer.

Once in the `Main Menu` map, first click on the `Host` button on one of them, and `Join` on the others (keep `127.0.0.1` as the ip address for a local testing).

The clients will join the host and you will be able to test the multiplayer.

## License

This project is under [Creative Common 0 license](LICENSE).  
![CC0-License](https://licensebuttons.net/p/zero/1.0/88x31.png)

## *Support Me*

If you like my plugin and/or this example project, please consider tipping:

[![Ko-fi](https://img.shields.io/badge/Ko--fi-FF5E5B?logo=kofi&logoColor=fff&style=for-the-badge)](https://ko-fi.com/M4M3NW2JV)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=000&style=for-the-badge)](https://buymeacoffee.com/benpyton)
[![Liberapay](https://img.shields.io/badge/Liberapay-F6C915?logo=liberapay&logoColor=000&style=for-the-badge)](https://liberapay.com/BenPyton/donate)
[![PayPal](https://img.shields.io/badge/PayPal-003087?logo=paypal&logoColor=fff&style=for-the-badge)](https://www.paypal.com/donate/?hosted_button_id=9VWP66JU5DZXN)

[1]: https://github.com/BenPyton/ProceduralDungeon
