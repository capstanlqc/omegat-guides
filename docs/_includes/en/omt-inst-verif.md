# OmegaT 5.7.4 setup guide for Windows

This document guides you through the process of installing OmegaT 5.7.4 in your machine. OmegaT 5.7.4 is a custom version prepared by cApStAn which includes several enhancements and bug fixes not available (yet) in the official release.

<!-- prettier-ignore -->
??? info "Mac and Linux operating systems"
    It's possible to install OmegaT in other operating systems like macOS or Linux. Please follow this [guide](install-and-setup-macos.md) to install on macOS. Please get in touch through the Helpdesk if you are a Linux user.


## Installation

<!-- prettier-ignore -->
!!! warning "A 64-bit machine is required to install OmegaT."
    

1.  Click on the button below to download OmegaT 5.7.4.

    [ :material-download: Download OmegaT 5.7.4](https://cat.capstan.be/OmegaT/exe/OmegaT_5.7.4_Windows_64_Signed.exe){ .md-button .md-button--primary }

    <!-- prettier-ignore -->
    ??? question "Trouble to download?"
        Some browsers (e.g. Microsoft Edge) might ask you whether downloading the installer is safe. It is safe, and you can follow the  steps in the video below to let your Edge browser download the file (or you can use another browser ;)

        ![](../_img/edge-keep-download.gif)

2.  When the download is complete, double-click the installer file to start the installation wizard.

3.  Windows Defender might show a warning about running an unrecognized app.

    ![](../_img/omegat-win-protected-your-pc-01.png) <!-- # omt572-install-01.png -->s

    If you see that, click on the <u>More info</u> link in that dialog. In the information displayed you should see that cApStAn is the publisher of this installer.

    ![](../_img/omt572-install-02-run-anyway.png)

    If that's the case, prease press the **Run anyway** button to proceed with the installation.

4.  In the next dialog, you may choose the language of the installation, then press **Ok**.

    ![](../_img/omt572-install-03-lang.png)

5.  Please accept the GPL license agreement to proceed, and press **Next**.

    ![](../_img/omt572-install-04-accept.png)

6.  OmegaT will propose the path `C:\Users\USER\AppData\Local\Programs\OmegaT` for the installation, where it should be possible for non-admin users to install. **Do not change this path.**

    ![](../_img/omt572-install-05-path.png)

    <!-- prettier-ignore -->
    !!! warning "Warning"
        Please do not modify this installation path unless you're IT personnel and you know what you're doing.

7.  You may modify the name of the OmegaT folder in the start menu, but "OmegaT " is fine, no need to change it.

    ![](../_img/omt572-install-07-start-menu.png)

8.  The setup wizard may create a desktop shortcut (launcher) on your Desktop, which you can double-click later on to launch OmegaT. Make sure this option is checked.

    ![](../_img/omt572-install-06-desktop-shortcut.png)

9.  You're ready to proceed with the installation, just press **Next**.

    ![](../_img/omt572-install-08-ready.png)

10. After a couple of minutes, your installation should be complete.

    ![](../_img/omt572-install-09-done.png)


Please go through the **Configuration** section below.


## Configuration

Your OmegaT installation must be configured with some custom files. 

### Automatically

If you have installed OmegaT from scratch in a machine where OmegaT had not been installed before, OmegaT should be configured automatically for you the first time you run it. The same thing will also happen every time an update of the custom configuration is released. 

When a new configuration update is being installed, you will see the following dialog: 

![](../_img/customization-update-running.png)

And you will see a dialog like this when the configuration is updated:

![](../_img/customization-update-finished.png)

If you saw the above dialog stating that a custom configuration update was installed right after installing OmegaT for the first time, you should be good to go. Just go to the [Setup checks](#setup-checks) section further down below to know how to run a few post-installation checks to confirm that everything is okay.

If you didn't see the above dialog, then something went wrong, but no worries, you can easily install the configuration manually. Just keep reading (the "Manually" section).

### Manually

If for any reason the automatic update above does not work, you may run the configuration script manually. 

You should already have the script that installs the latest configuration (called "Update Customization Bundle"). You may select the shortcut 12 at the bottom of the list of script shortcuts below the **Tools** > **Scripting** menu to run the "Update Customization Bundle" script: 

![](../_img/script-shortcut-12.png)

Alternatively (if for some reason you can't see shortcut #12), you may open the **Scripting** menu and run the script from there. Select the script "Update Customization Bundle" in the list and then press the **Run** button. 

![](../_img/config-script-run-manually.png)

!!! warning
    If something is wrong and you don't have that script, please get in touch in our Helpdesk.

   
See the section below to know how to run a few post-installation checks to confirm that everything is okay.

## Setup checks

The steps above will normally get up and running, but but it's always a good idea to check that everything is okay just in case. One stick in time saves nine. These are the things that you can check:

1.  _OmegaT version_

    To confirm that you have the correct version, you can check that in **Help** > **About** > **Copy Support Info**. You should see:

        Version: OmegaT-5.7.4_0_57b1bb571
        Platform: Windows 10 10.0
        Java: 11.0.19 amd64

2.  _Custom configuration version_

    To confirm that your custom configuration is up to date, you can go to **Options** > **Access Configuration Folder** and find a file called `local_version_notes.txt` there.

    If you open that file, the line at the top showing the most recent update should be the same as the one you can see in page [https://cat.capstan.be/OmegaT/v572/](https://cat.capstan.be/OmegaT/v572/).

3.  _OMT un/packaging menu entries_

    Even if you don't use OMT packages, you should have three entries under the **Project** menu in OmegaT:

    ![](../_img/omt-package-entries.png)

    <!-- - Unpack project from OMT file...
    - Pack project as OMT file...
    - Pack and delete project...  -->

4.  _Scripts and script shortcuts_

    In the **Tools** menu, under **Scripting**, you should see a list of 12 script shortcuts.

    ![](../_img/omt-scripts-shortcuts.png)

    !!! note
        The script shortcuts might be updated occasionally, don't worry if your list is not identical to the screenshot above.

    Also, if you open the scripting dialog, you should see the whole list of scripts on the left-hand side.

You're done now. You can start using OmegaT.

<!--
To install OmegaT and set it up on a computer running Windows, please follow the OmegaT installation and setup guide below:

<div style="width: 100%">

<iframe
src="https://slides.com/capstan/omegat-v572-setup-guide/embed?byline=hidden&share=hidden"
width="100%"
height="420"
scrolling="no"
frameborder="0"
webkitallowfullscreen mozallowfullscreen allowfullscreen>
</iframe>

</div>

If you use Mac or Linux, please see the second slide above or get in touch through the Helpdesk.


- USB
16GBc
model...
format as FAT32
D:\OmegaT
zip -- iso


https://www.westerndigital.com/products/usb-flash-drives/sandisk-ultra-fit-usb-3-1?sku=SDCZ430-016G-G46

-->
