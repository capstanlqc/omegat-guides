# Auxiliary tools

## AutoHotKey (e.g. to insert no-break spaces)

If you need to insert non-breaking spaces in your translation, you can use the [autotext](autotext.md) entry `\nbsp`. However, if this is not convenient (e.g. because you need to insert no-break spaces veeeery often) you can use a AutoHotKey script on Windows.

AutoHotKey is a standalone software and has nothing to do with OmegaT. The AutoHotKey script can be used to insert autotext (e.g. the no-break space in this case) in any other application in your system.

!!! info
    AutoHotKey is a Windows-only application. If you're on Mac or Linux, you should find an alternative way to insert non-breaking spaces. Perhaps your operating system natively supports autotext without the need to install third-party apps.

### How to install the AutoHotKey script

Follow these steps: 

1. Download and install [AutoHotKey](https://www.autohotkey.com/download/).
1. Press **Win+R** on your keyboard, paste `shell:startup` and press OK. The startup folder opens up.
1. Right-click the following [link to the AHK script](https://cat.capstan.be/OmegaT/auxiliary/nbsp.ahk), select “Save link as” and save the `nbsp.ahk` script in your startup folder.
1. In the startup folder, right-click the script file (`nbsp.ahk`) and choose **Run script**.

 This script will be run automatically the next time your machine starts.

<!-- @ŧodo: add link to this in the tips and tricks  and FAQ -->

!!! info
    You're free to install AutoHotKey and use the AutoHotKey that we provide for your convenience using the steps above. However, we cannot provide support for AutoHotKey. You can find help in the [AutoHotKey](https://www.autohotkey.com/boards/) community.


### How to insert the no-break space:

1. Click in the position in the text where you want to insert the non-breaking space.
1. Press ++ctrl+shift+space++.

<!-- 
author ahk scripts in the server 
https://cat.capstan.be/OmegaT/auxiliary/insert_unicode_char.ahk
http://capps.capstan.be/cat/insert_nobreak_sp.ahk
-->