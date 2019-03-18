# Android Q modifications
This enables hidden settings in android Q in the form of an executable script

## How to Use?
Open a terminal app and su or adb shell and run "qmod"

## What features are listed?
Currently there is dark theming, new navbar gestures, lockscreen clocks, desktop mode, and chat bubbles. 
More information is in the script itself

## Compatibility
* Android Q+

## To download the script (non-root, in a terminal)
	curl https://raw.githubusercontent.com/bdashore3/q_tweaks/q_master/system/bin/qmod > /sdcard/qmod

## To execute the script
Root: Just type qmod in a terminal (preferably su)

Non-root (in an adb shell): 
* chmod 0777 /sdcard/qmod
* sh /sdcard/qmod


