# ⌨ ✔ Intellij Keyboard Layout Fix

This is workaround for IntelliJ on a German keyboard which produces an annoying `µ` on `extract method`-action.  
For now [this bug [IDEA-187355]](https://youtrack.jetbrains.com/issue/IDEA-187355) isn't fixed so we help us out by removing the letter `µ`.  
This is done by a keyboard which is created by the [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339).

## Download

:package: [IntelliJ_keyboard_layout_fix_setup.zip](https://github.com/TobseF/intellij-keyboard-fix/releases/tag/1.0.0)

## Install

 1. Extract, run and install `setup.exe`.
 2. Go to: _Einstelungen >  Eingabeeinstellungen > Standardeingabemethode > Deutsch - Custom_

![windows settings](images/windows_settings.png?raw=true)

![keyboard settings](images/keyboard_settings.png?raw=true)

## Alternative: Build setup by your own

If you don't trust the provided setup you can build your own by the provided config file:

 1. Download, install and run the [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339).
 2. Load the `Keyboard Layout DE - IntelliJ.klc`.
 3. Create the setup.
 4. Follow with step _Install_.
