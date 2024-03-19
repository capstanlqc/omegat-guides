# OmegaT 5.7.2 setup guide for Windows

??? info "Other operating systems"
    It's possible to install OmegaT 5.7.2 in other operating systems like macOS or Linux. Follow this other [guide to install on macOS](../install-and-setup-macos/). Please get in touch through the Helpdesk if you are a Linux user.

Depending on your starting point, ==choose your path here carefully==:

- IF you already have a previous version (e.g. 5.7.1 or 4.2.0) of OmegaT installed, you'll have to update your configuration first: to do so please go to the [configuration section](#configuration) (next section right down below).
- IF you have _never_ installed there OmegaT (any version) in your machine, you can skip the following section about configuration and jump directly to the [installation section](#installation). OmegaT will configure itself as part of the installation.

## Configuration

This section applies to users that already have a previous version (e.g. 5.7.1 or 4.2.0) of OmegaT installed. Please follow the next steps to update your configuration.

1. Run OmegaT and go to **Tools** > **Scripting** to open your scripting console,  In OmegaT 5.7.1, please open the scripting console. Check whethers you have a script called "**Update Customisation Bundle (v572)**":

   !!! warning
       If you don't see the "**v572**" bit, then it's not the script we're looking for. See next step to fetch the script.

   ![](../_assets/img/custom-script-572-in-scripting-console.png)


   If the script "**Update Customisation Bundle (v572)**" is there, please click on it to select it and press the **Run** button (at the bottom left) to run it. The script will run to update your config files and will quit OmegaT. After that, skip the next step and jump directly to the [installation section](#installation).

   If the script is not there, you may download it yourself. See next steps for how to do that.

2. Right-click on the button below and select "Save Link As" to download the configuration script (e.g. to your Desktop)

   [:material-download: Download UpdateConfigBundle.groovy](https://cat.capstan.be/OmegaT/customization/scripts/updateConfigBundle-572.groovy){ .md-button .md-button--primary }


3. In OmegaT, follow these steps to run the configuration script you have downloaded:
   - **Tools** > **Scripting** > **File** > **Open script**
   - browse to your Desktop (or the folder where you have saved the script) and select the groovy file
   - press the **Open** button to open the script file and press **Run** button (on the bottom left)

   ![](../_assets/img/omt-open-script-and-run.gif)

   The script will install the necessary config files for OmegaT 5.7.2 and delete old config files for OmegaT 5.7.1, and after that it will quit OmegaT.

4. Uninstall your current version of OmegaT.

5. Finally, proceed now to the [installation section](#installation) (next step below).


## Installation

!!! warning
    You must have a 64-bit machine to install OmegaT. If that's not the case, please get in touch with our Helpdesk.

1. Click on the button below to download OmegaT 5.7.2. This is a custom version prepared by cApStAn which includes several bug fixes and enhancements not available in other versions.

   [:material-download: Download OmegaT 5.7.2](https://cat.capstan.be/OmegaT/exe/OmegaT_5.7.2_Windows_64_Signed.exe){ .md-button .md-button--primary }

   ??? question "Trouble to download?"
       Some browsers (e.g. Microsoft Edge) might ask you whether downloading the installer is safe. It is safe, and you can follow the following steps in the video below to let your browser download the file.
       ![](../_assets/img/edge-keep-download.gif)

2. When the download is complete, double-click the installer file to start the installation wizard.

3. Windows Defender might show a dialog warning against the risk of running an unrecognized app.

   ![](../_assets/img/omegat-win-protected-your-pc-01.png) <!-- # omt572-install-01.png -->s

   If you see that, click on the <u>More info</u> link in that dialog. In the information displayed you should see that cApStAn is the publisher of this installer.

   ![](../_assets/img/omt572-install-02-run-anyway.png)

   If that's the case, prease press the **Run anyway** button to proceed with the installation.

4. In the next dialog, you may choose the language of the installation, then press **Ok**:

   ![](../_assets/img/omt572-install-03-lang.png)

5. Please accept the GPL license agreement to proceed, and press **Next**:

   ![](../_assets/img/omt572-install-04-accept.png)

6. OmegaT will propose the path `C:\Users\USER\AppData\Local\Programs\OmegaT` for the installation, where it should be possible for non-admin users to install.

   !!! warning
       Please do not modify this installation path unless you're IT personnel and you know what you're doing.

   ![](../_assets/img/omt572-install-05-path.png)

7. A desktop shortcut (launcher) will be created on your Desktop (which you can double-click later on to launch OmegaT). Do not uncheck that option.

   ![](../_assets/img/omt572-install-06-desktop-shortcut.png)

8. You may modify the name of the OmegaT folder in the start menu, but "OmegaT " is fine, no need to change it in a standard installation.

   ![](../_assets/img/omt572-install-07-start-menu.png)

9. You're ready to proceed with the installation, press **Next**.

   ![](../_assets/img/omt572-install-08-ready.png)

10. After a couple of minutes, your installation should be complete.

   ![](../_assets/img/omt572-install-09-done.png)

11. See the section below to know how to run a few post-installation checks to confirm that everything is okay.

You're done now. You can start using OmegaT 5.7.2.

## Setup checks

The steps above will normally get up and running, but but it's always a good idea to check that everything is okay just in case. One stick in time saves nine. These are the things that you can check:

1. _OmegaT version_

   To confirm that you have the correct version, you can check that in **Help** > **About** > **Copy Support Info**. You should see:

        > Version: OmegaT-5.7.2_0_a978d82ee   
        > Platform: [your operating system]  
        > Java: 11.0.19 amd64

2. _Custom configuration version_

   To confirm that your custom configuration is up to date, you can go to **Options** > **Access Configuration Folder** and find a file called `local_version_notes.txt` there.

   If you open that file, the line at the top showing the most recent update should be the same as the one you can see in page [https://cat.capstan.be/OmegaT/v572/](https://cat.capstan.be/OmegaT/v572/).

3. _OMT un/packaging menu entries_

   Even if you don't use OMT packages, you should have three entries under the **Project** menu in OmegaT:

   ![](../_assets/img/omt-package-entries.png)

   <!-- - Unpack project from OMT file...
       - Pack project as OMT file...
       - Pack and delete project...  -->

4. _Scripts and script shortcuts_

   In the **Tools** menu, under **Scripting**, you should see a list of 12 script shortcuts.

   ![](../_assets/img/omt-scripts-shortcuts.png)

   !!! note
       The script shortcuts might be updated occasionally, don't worry if your list is not identical to the screenshot above.

   Also, if you open the scripting dialog, you should see the whole list of scripts on the left-hand side.






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
