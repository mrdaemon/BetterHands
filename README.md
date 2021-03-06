# BetterHands
[![version](https://img.shields.io/github/v/release/Maiq-The-Dude/BetterHands?&label=version&style=flat-square)](https://github.com/Maiq-The-Dude/BetterHands/releases/latest) [![discord](https://img.shields.io/discord/777351065950879744?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2&style=flat-square)](https://discord.gg/g8xeFyt42j)

Mod for H3VR to recolor controller geo, resize interaction spheres, and add mag palming.
All features are optional and configured via `mods/configs/betterhands.cfg`. Configs can be edited mid-game, but will require a scene reload to take effect.

## Mag Palming
Mag palming allows you to carry two small sized magazines in one hand. To do this click the trigger when holding a magazine in your hand.

### Mag Palming Configs
- Change mag palm pose position and rotation
- Change click pressure required to mag palm
- Change priority of Grabbity Gloves vs mag palming
- Change palmable mag size limit. **Greater than `Medium` will disable TNH score submission**
- Toggle `CursedPalms` which allows any interactive object to be palmed. Use at your own risk, bugs stemming from this will rarely be investigated. **Disables TNH score submission**
- Toggle `Interactable` which allows palmed items to be directly grabbed by the other hand
- Rebind mag palm key
  - AX/BY buttons
  - Grip
  - Joystick
  - Touchpad directional taps
  - Touchpad directional clicks
  - Trigger (default)

## Hand Customization
- Recolor controller geo
- Recolor interaction spheres
- Resize individual interaction spheres

## Installation
Requires [BepInEx 5.4](https://github.com/BepInEx/BepInEx/releases/latest) and [Deli 0.2.5](https://github.com/Deli-Collective/Deli/releases/tag/v0.2.5).

Download the [latest release of BetterHands](https://github.com/Maiq-The-Dude/BetterHands/releases/latest) and place `betterhands.deli` into `h3vr/mods` folder.

## Uninstallation
Delete `betterhands.deli` in the `h3vr/mods` folder and `betterhands.cfg` in the `h3vr/mods/configs` folder.
