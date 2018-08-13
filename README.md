# Touchpad_toggle

This is a shell script that will toggle a laptop's touchpad on and off. The script was written so that the manufacturer of the laptop/touchpad does not matter. 

# Installation 

## Dependencies 

* Requires `xinput` (odds are most Linux distro have it pre-installed)

## Installing

Simply make the script executable, this can be done via `sudo chmod a+x Touchpad_toggle`

# Usage

This script can be either used manually in a terminal or bound to a hotkey in your preferred Window Manager/Desktop Environment (recommended) 

The script has no parameters, simply run the command and depending if the touchpad is enabled or disabled, the output is either "trackpad disabled" or "trackpad enabled".

When it comes to binding it to a hotkey, a good option is XF86TouchpadToggle, which represents the toggle touchpad media key on most laptops - provided said laptop has the key. 
