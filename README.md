![screenshot](https://raw.githubusercontent.com/jeffThompson/DarkArduinoTheme/master/screenshot.png)

Dark Arduino Theme
================

Revised for Arduino version 1.8.5+, not tested with earlier versions.

\- \- \-

### INSTALLATION  

* Mac users should look in `~/Applications/Arduino.app/Contents/Java/lib` and replace the `theme` folder inside (making a copy of the original in case want to revert back).  
* Windows Desktop version is located in `C:\Program Files (x86)\Arduino\lib`. 
* Windows Microsoft Store App version supports selectable themes. Create a folder named `theme` inside your sketchbook folder. Within this new folder, create a zip file named `Dark theme.zip` containing only the files under `CDarkArduinoTheme/theme/` from this project. Start the IDE and open preferences (Shortcut: Ctrl+Comma). Change `Theme` setting from `Default theme` to `Dark theme`. Click OK and then close and restart the IDE.
* Linux will be in `/usr/share/arduino/lib/` – note you may need to install the Arduino IDE from the Arduino site, not a place like Ubuntu Software  

### CREATING YOUR OWN MODS
The newest version of the Arduino IDE makes creating custom themes trickier: you now need to edit the `theme.txt` file, an XML file inside the `syntax` folder, and the button files. Unfortunately, not all items in the `theme.txt` file actually work, so if you can't get an item to change, try another one of the files.

\- \- \-

Released under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org).
