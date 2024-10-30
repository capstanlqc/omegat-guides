# OmegaT 5.7.2 setup guide for macOS

This document guides you through the process of installing OmegaT 5.7.3 in your machine. This is a custom version prepared by cApStAn which includes several enhancements and bug fixes not available in the official release.

<!-- prettier-ignore -->
??? warning "Are you a Windows user?"
    Do not use this guide if you are a Windows user. In that case, please refer to the [guide](install-and-setup.md) to install on Windows. 


## Installation

1. Click on the button below to download OmegaT 5.7.3. 

    [ :material-download: Download OmegaT 5.7.3](https://cat.capstan.be/OmegaT/exe/OmegaT_5.7.3_Mac.zip){ .md-button .md-button--primary }

2. If you're using Safari, then the file will be unzipped automatically when the download ends.​ If you use another browser, double-click the file when the download ends to unzip it.

3. A folder is created, open it to see its contents. You'll see that it contains the **OmegaT.app** file.

4. Drag the **OmegaT.app** file to the **Applications** folder.

    <div data-block-type="video" style="width: 480px; height: 304px; left: 400px; top: 326px;">
        <div class="sl-block-content" style="z-index: 10;" data-media-id="8242406" data-video-thumb="https://s3.amazonaws.com/media-p.slid.es/videos/1129410/Sjlk4rKG/1kx16dhvq0_thumb_00001.jpg"><video playsinline="" controls="controls" poster="https://s3.amazonaws.com/media-p.slid.es/videos/1129410/Sjlk4rKG/1kx16dhvq0_thumb_00001.jpg" data-paused-by-reveal="" data-lazy-loaded="" src="https://s3.amazonaws.com/media-p.slid.es/videos/1129410/Sjlk4rKG/1kx16dhvq0.mp4"></video></div>
    </div>

5. OmegaT is now installed. Go to the **Applications** folder and open **OmegaT** there.
6. Your Mac might ask for confirmation that you want to open it. If that's the case, please press **Open**. OmegaT will now run.

    <div data-block-type="video" style="width: 480px; height: 304px; left: 400px; top: 326px;" >
        <div class="sl-block-content" style="z-index: 10;" data-media-id="8242392" data-video-thumb="https://s3.amazonaws.com/media-p.slid.es/videos/1129410/eXYV2O_T/oiepooibjr_thumb_00001.jpg"><video playsinline="" controls="controls" poster="https://s3.amazonaws.com/media-p.slid.es/videos/1129410/eXYV2O_T/oiepooibjr_thumb_00001.jpg" data-lazy-loaded="" data-paused-by-reveal="" src="https://s3.amazonaws.com/media-p.slid.es/videos/1129410/eXYV2O_T/oiepooibjr.mp4"></video></div>
    </div>

7. If you want to run a post-installation check to confirm that you have the correct version, you can check that in **Help** > **About** > **Copy Support Info**. You should see:

        > Version: OmegaT-5.7.3_0_57b1bb571
        > Platform: Windows 10 10.0
        > Java: 11.0.19 amd64


## Configuration

The OmegaT installation must be configured with some custom files. Please follow the next steps to install or update your configuration.

1. Run OmegaT and go to **Tools** > **Scripting** to open your scripting console, Check whether you have a script called "**Update Customisation Bundle**"

    ![](../_img/custom-script-572-in-scripting-console_Mac.png)

2. If the script "**Update Customisation Bundle**" is there, please click on it to select it and press the **Run** button (at the bottom left) to run it. The script will run to update your config files and will quit OmegaT. 

##### If you don't have the script, here's a fallback plan

If the script is not there, you may download it yourself. See next steps for how to do that.

2. Right-click on the button below and select "Save Link As" to download the configuration script (e.g. to your Desktop)

    [ :material-download: Download UpdateConfigBundle.groovy](https://cat.capstan.be/OmegaT/v572/customization/scripts/updateConfigBundle.groovy){ .md-button .md-button--primary }

3. In OmegaT, follow these steps to run the configuration script you have downloaded:

    - **Tools** > **Scripting** > **File** > **Open script**
    - browse to your Desktop (or the folder where you have saved the script) and select the groovy file
    - press the **Open** button to open the script file and press **Run** button (on the bottom left)

    ![](../_img/omt-open-script-and-run_Mac.gif)

    The script will install the necessary config files, and after that it will quit OmegaT.


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
