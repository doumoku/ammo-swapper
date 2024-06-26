# FoundryVTT - Forien's Ammo Swapper
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/Foundry-Workshop/ammo-swapper?style=for-the-badge)
![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2FFoundry-Workshop%2Fammo-swapper%2Fmaster%2Fdist%2Fmodule.json&label=Foundry%20Min%20Version&query=$.compatibility.minimum&colorB=orange&style=for-the-badge)
![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2FFoundry-Workshop%2Fammo-swapper%2Fmaster%2Fdist%2Fmodule.json&label=Foundry%20Verified&query=$.compatibility.verified&colorB=orange&style=for-the-badge)  
![License](https://img.shields.io/github/license/Foundry-Workshop/ammo-swapper?style=for-the-badge) ![GitHub Releases](https://img.shields.io/github/downloads/Foundry-Workshop/ammo-swapper/latest/module.zip?style=for-the-badge)
![GitHub All Releases](https://img.shields.io/github/downloads/Foundry-Workshop/ammo-swapper/module.zip?style=for-the-badge&label=Downloads+total)  
[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white&link=https%3A%2F%2Fdiscord.gg%2FXkTFv8DRDc)](https://discord.gg/XkTFv8DRDc)
[![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/foundryworkshop)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/forien)  

**[Systems]**: *WFRP4e, DnD5e,PF2e, PF1, SFRPG*  
**[Languages]**: *English*  

This module for Foundry Virtual Tabletop adds HUD allowing to easily swap which ammunition is being used in ranged weapons. 

## Installation

1. Install Forien's Ammo Swapper using manifest URL: https://raw.githubusercontent.com/Foundry-Workshop/ammo-swapper/master/src/module.json
2. While loaded in World, enable **_Forien's Ammo Swapper_** module.

## Usage

### As Player
* Assign character to your user account
* Equip ranged weapon(s)
* Click on HUD displayed on bottom of your screen to bring out selectable list of owned ammunition
* Click on any ammunition on the list to change weapon's ammunition
* **If `show only equipped` setting is disabled** Right-Click on weapon to toggle its equipped state!

### As Game Master
* You can either use the module like the Players (via assigned character),
* Or you can use it by selecting tokens on the canvas. 

## Screenshots
<img src="https://i.gyazo.com/b32cfb70d45d3368750cb1ee80c95a0d.png" alt="screenshot"/>
<img src="https://i.imgur.com/JudSxFH.png" alt="screenshot"/>

## Future plans

You can **always** check current and up-to-date [planned and requested features here](https://github.com/Foundry-Workshop/ammo-swapper/issues?q=is%3Aopen+is%3Aissue+label%3Aenhancement)

*If you have **any** suggestion or idea on new contents, hit me up on Discord!*

## System support

* Module supports following systems:
  * DnD5e (tested version 2.4.1)
  * PF1 (tested version 9.6)
  * PF2e (tested version 5.12.7)
  * SFRPG (tested version 0.25.2)
  * WFRP4e (tested version 7.1.0)
* Module displays only weapons/ammunition that exist on the Actor, using data from that Actor.
* Module doesn't include any weapons and/or ammunition Items.
* Module should work fine with any custom weapons/ammo created for supported systems.

For additional support (for example other systems) please open an [issue](https://github.com/Foundry-Workshop/ammo-swapper/issues), or you can use the API to include support within your system/module.

## Contact

If you wish to contact me for any reason, reach me out on Discord using my handle: `forien`

## Support

If you wish to support module development, please consider [becoming Patron](https://www.patreon.com/foundryworkshop).


## License

Forien's Ammo Swapper is a module for Foundry VTT by Forien and is licensed under a MIT License.

This work is licensed under Foundry Virtual Tabletop [EULA - Limited License for Package Development from March 2, 2023](https://foundryvtt.com/article/license/).
