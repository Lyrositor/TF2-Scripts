TF2-Scripts
===========

*A collection of scripts I have found to be useful for playing Team Fortress 2.*

## Features ##
Most features are usable by all classes, but a few are class-specific. If you would like to see more features implemented send me a message and I'll do my best, if I find it interesting:
* **Debug Output:** prints debug messages to the screen (such as current spy disguise and so on).
* **Auto Crouch-Jump:** automatically makes you crouch-jump when playing the spacebar.
* **Loadout Switch:** binds 4 Shift key combinations to each loadout.
* **Netgraph:** displays the netgraph on the score screen (Tab key).
* **Spy-Checking Lines:** sends a team message notifying players about an exposed spy (e.g. "Pyro is Spy.").
* **Suicide Explosion:** makes you explode at the touch of a button.
* **Engineer: Building Bindings:** binds keys 6 through 9 to the Engineer's buildings, automatically destroying any existing buildings when pressed.
* **Spy: Disguise Bindings:** binds key 5 through 9 to some of the Spy's disguises.
* **Spy: Auto Disguise:** automatically disguises the Spy on left-click. If this is not desirable (for example, when placing a sapper), use MOUSE3 to perform a normal left-click. Also automatically changes the disguise's current weapon when actually switching weapons. Press F at any time to disable all auto disguise functions.

### Settings ###
TF2-Scripts comes with several settings used to disable certain undesired features; edit them in `cfg\scripts\settings.cfg`:
* `AUTO_CROUCH_JUMP`
* `AUTO_DISGUISE`
* `CLEAR_CONSOLE_ON_START`
* `LOADOUT_SWITCH`
* `SHOW_NETGRAPH`
* `SPY_LINES`
* `SUICIDE_EXPLOSION`

## Installation ##
To install, locate your Team Fortress 2 installation's `custom` folder (usually located at `C:\Program Files (x86)\Steam\SteamApps\common\Team Fortress 2\tf\custom` on Windows), then copy-and-paste the `TF2-Scripts` there.
