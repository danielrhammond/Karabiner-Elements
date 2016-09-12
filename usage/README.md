* [Installation](#installation)
* [Open Karabiner-Elements](#open-karabiner-elements)
* [Quit Karabiner-Elements](#quit-karabiner-elements)
* [Uninstall Karabiner-Elements](#uninstall-karabiner-elements)
* [Change Key](#change-key)

# Installation

Download Karabiner-Elements package from https://pqrs.org/latest/karabiner-elements-latest.dmg

Open dmg file and then open the installer.

Karabiner-Elements and Karabiner-EventViewer will be installed into Launchpad.

<img src="img/installed.png" width="400">

# Open Karabiner-Elements

Open Karabiner-Elements from Launchpad.

The preferences window will be opened.

<img src="img/preferences.png" width="400">

# Quit Karabiner-Elements

You can quit Karabiner-Elements by the Quit Karabiner-Elements button.

<img src="img/quit.png" width="400">

# Uninstall Karabiner-Elements

You can uninstall Karabiner-Elements from Misc tab.

<img src="img/uninstall.png" width="400">

# Change Key

At the moment, you have to edit the configuration file by hand.

The configuration file is located in `~/.karabiner.d/configuration/karabiner.json`

```json
{
    "profiles": [
        {
            "name": "Default profile",
            "selected": true,
            "simple_modifications": {
                "caps_lock": "delete"
            }
        }
    ]
}
```