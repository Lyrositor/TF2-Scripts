TF2-Scripts
===========

*A collection of scripts I have found to be useful for playing Team Fortress 2.*

**Github Link:** [Lyrositor/TF2-Scripts](https://github.com/Lyrositor/TF2-Scripts)

**GAMEBANANA Link:** [TF2 Scripts - Script Collection](http://tf2.gamebanana.com/scripts/8373)

**Note:** this collection makes no use of `wait` commands, ensuring maximum compatibility on all servers.

## Features ##
Most features are usable by all classes, but a few are class-specific. If you would like to see more features implemented send me a message and I'll do my best, if I find it interesting:

- **Debug Output:** prints debug messages to the screen using captions (such as current spy disguise and so on).
- **Auto Crouch-Jump:** automatically makes you crouch-jump when playing the spacebar.
- **Loadout Switch:** binds 4 `Shift` key combinations to each loadout.
- **Music Player:** cycles through Team Fortress 2's music files when pressing the `;` key. Can also automatically play a song on class select.
- **Netgraph:** displays the netgraph on the score screen (`Tab` key).
- **Pyro Airblast Call:** sends a team message asking for a Pyro to airblast you by pressing `Backspace`.
- **Spy-Checking Lines:** sends a team message notifying players about an exposed spy (e.g. "Pyro is Spy.") by pressing `Shift` + the class' number (1-9).
- **Suicide Explosion:** makes you explode at the touch of a button.
- **Viewmodel Toggling:** toggles display of the active weapon at the press of the `Delete` key.
- **Engineer: Building Bindings:** binds keys 6 through 9 to the Engineer's buildings, automatically destroying any existing buildings when pressed. You can also disable the PDA numeric keys; doing so will shift the building bindings from 6-9 to 4-7.
- **Soldier: Rocket Jump:** a simple rocket jump script bound to `MOUSE2` when toggled on (use `R` to toggle). Does not provide optimal jump, but is a reliable way to rocket jump. Aim the rocket launcher at the ground before clicking.
- **Spy: Taunt:** automatically un-disguises the Spy before performing a taunt. If pressing `G` once doesn't work for you, always quickly press `G` twice.
- **Spy: Disguise Bindings:** binds key 5 through 9 to some of the Spy's disguises.
- **Spy: Auto Disguise:** automatically disguises the Spy on clicking `MOUSE1`. If this is not desirable (for example, when placing a sapper), use `MOUSE3` to perform a normal left-click. Also automatically changes the disguise's current weapon when actually switching weapons. Press `F` at any time to disable all auto disguise functions.

### Settings ###
TF2-Scripts comes with several settings used to disable certain undesired features; edit them in `cfg\_settings.cfg`:

- `AUTO_CROUCH_JUMP`
- `AUTO_DISGUISE`
- `CLEAR_CONSOLE_ON_START`
- `DEBUG_OUTPUT_ON_START`
- `ENGINEER_PDA`
- `MUSIC_PLAYER`
- `MUSIC_PLAYER_CLASSES`
- `LOADOUT_SWITCH`
- `SHOW_NETGRAPH`
- `SOLDIER_ROCKET_JUMP`
- `SPY_LINES`
- `SPY_TAUNT`
- `SUICIDE_EXPLOSION`

## Installation ##
To install, locate your Team Fortress 2 installation's `custom` folder (usually located at `C:\Program Files (x86)\Steam\SteamApps\common\Team Fortress 2\tf\custom` on Windows), then copy-and-paste the `TF2-Scripts` there.

## Credits ##
The scripts bundled together would not have been possibly were it not for the scripts and tutorials provided by the following people:

- The [Team Fortress 2 Wiki](http://wiki.teamfortress.com) contributors for their scripting tutorials,
- [Zoolooman](http://wiki.teamfortress.com/wiki/User:Zoolooman) for his `echo` [tutorial](http://wiki.teamfortress.com/wiki/User:Zoolooman/Scripting),
- Dr.Device's [Toggle Auto Disguise on attack V1.2](http://tf2wiki.net/wiki/spy_scripts#Toggle_Auto_Disguise_on_attack) script for Spy, upon which the auto disguise functionality is based,
- [TheFifthWheel](http://gamebanana.com/members/1350351)'s [TF2 Jukebox Script](http://tf2.gamebanana.com/scripts/8268), used as inspiration for the music player (special thanks for providing the names of the music files),
- INsane for his [developer console font file information](http://www.dodbits.com/dods/index.php/source-graphics/source-gui-hud-tutorials/33-console-font-color-and-size),
- [clovervidia](http://steamcommunity.com/id/clovervidia/) for his [captions tutorials](http://www.reddit.com/r/tf2scripthelp/wiki/captions),
- josh33901 for his rocket jump suggestion.

As best as I can recall, all other scripts are written by me, using various tutorials and my own discoveries. If you feel your script was not credited, or you want me to cease distributing your script, send me a message and I will either add credit where it is due or remove your script.