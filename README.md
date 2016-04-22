# Galaban's Sleep Monitor
This is a base plugin for the Shattered Isles mud to monitor your health while sleeping.

This plugin is used as a launching point.  You can modify it to call custom actions or play sounsd.  Or you can hook off of the plugin broadcast to do such things.

I, personally, watch for the broadcast and use it to play a sound.

If you wish to modify it, just look for the "healingComplete()" function and modify that to do what you want to do.

## Requirements
For this to work, you must have a prompt that contains a > character (preferably at the end).  Also, you must end your prompt with a new line character (%B) to insure that the plugin picks it up.

## To install
1. Download the raw file from github:
https://raw.github.com/galaban/ShatteredIsles_SleepMonitor/master/Galabans_SleepMonitor.xml
2. Place the raw file into your "plugins" directory.  This is fund in your Mushclient folder under /worlds/plugins.
3. Install the plugain in MushClient.  From the "File" menu, choose "plugins", then "Add".  Select the file and choose "OK".
