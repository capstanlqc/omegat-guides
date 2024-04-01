<!-- #  OmegaT 6.1.0 installation and setup guide -->

# OmegaT 6.1.0 setup guide

OmegaT is the open source computer-assisted translation tool (CAT tool) which we use to translate, reconcile, adapt, review and verify materials. You must install OmegaT and set it up with some additional files, in order to ensure an optimal interface and compatibility with the project we'll prepare for you.

> In particular, OmegaT 6.1 is necessary to work with Myanmar languages.

## OmegaT version

Please:

- Download OmegaT 6.1.0 from the **link provided** in this guide. Do not download OmegaT from another link.
- Install OmegaT version 6.1.0 (from the link in this guide). Do not install **any other** version of OmegaT.

## Installation and configuration

Notice that the setup process to get you started consists of **two** steps:

1. Installing OmegaT
2. Installing your user configuration files

> Any configuration updates won't require re-installing OmegaT (unless exlicitedly noted).

If OmegaT is already installed in your machine but it's not version 6.1.0, please uninstall that version before proceeding. You can check OmegaT's version in the title bar.

![](https://capstanlqc.github.io/omegat-guid_img/omt-version-in-title.png)

<!-- Check the [¶ How to uninstall apps on Windows 10](#how-to-uninstall-apps-on-windows-10) section below if you're not sure how to proceed. -->

> If OmegaT 6.1.0 is already installed in your machine, you may skip the next section and go straight to the [1.3. Configure OmegaT](#13-configure-omegat) section below to proceed with the configuration (customization).

### 1.1. Download installer

<!-- Please download the OmegaT 6.1 installer from [here](https://nextcloud.capstan.be/index.php/s/8o4njsQszczNG7F). -->

<!-- Please download the cApStAn-signed OmegaT 6.1 installer from [here](https://nextcloud.capstan.be/index.php/s/PM9iQGRJFZbAfYP). -->

Please download the cApStAn-signed OmegaT 6.1 installer from [here](https://github.com/capstanlqc/omegat-guides/raw/master/lfs/OmegaT_6.1.0_Beta_Windows_64_Signed.exe).

> You must have a 64-bit machine to install this version of OmegaT. If that's not the case, please get in touch with our Helpdesk. <!-- Check the [¶ 64bit or 32bit machine?](#64bit-or-32bit-machine) section below if you're not sure how to check whether you have a 64-bit or 32-bit machine. -->

It's a safe download, even if your browser might not trust the file.

### 1.2. Install OmegaT

In order to proceed with the installation, please follow these steps:

- Double click the executable file (e.g. `OmegaT_6.1.0_Beta_Windows_64_Signed.exe`) that you have downloaded.

- Windows could display a blue screen saying that it might be risky to install OmegaT. If that's the case, click on "More info"

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-win-protected-your-pc-01.png)

   That will show information about the application and the publisher. You can be confidently press the **Run anyway** button as long as you see the publisher is cApStAn.

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-win-protected-your-pc-02.png)

- If you see the following screen, click on "Yes":

   <!-- https://imgur.com/g9oaURq.png -->

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-signed-installation-01.png)

- Choose (or keep) English as the language of the installation:

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-signed-installation-02.png)
   <!-- {: style="height:50%;width:50%"} -->

- Please also use English as the language of the OmegaT user interface:

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-signed-installation-03.png)
   <!-- {: style="height:70%;width:70%"} -->

- In the License Agreement screen, please select "I accept the agreement” and click “Next”:

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-signed-installation-04.png)<!-- {: style="height:70%;width:70%"} -->

- In all the next dialogs, just press “Next” to use the default options until you reach the **Ready to Install** screen.

- We recommend that you do not change the default installation path, just click Next in this screen:

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-signed-installation-05.png)

- We also recommend that you create a desktop shortcut (if that's a useful way for you to run OmegaT):

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-signed-installation-07.png)

- In the **Ready to Install** screen, click on “Install”.

   ![](https://capstanlqc.github.io/omegat-guid_img/omegat-signed-installation-08.png)<!-- {: style="height:70%;width:70%"} -->

- When the installation is finalized, you will see the last screen:

   ![](https://i.imgur.com/NGjakJv.png)

After that, you'll be able to run OmegaT from the OmegaT desktop shortcut icon (if you have created one) or from the applications menu.

### 1.3. Configure OmegaT

To configure OmegaT, please do:

- Launch OmegaT once and then close it.
- Launch OmegaT again and let it run for a few seconds.
- Close OmegaT.

During the second execution, OmegaT will be configured automatically in the brackground. When you run OmegaT for the third time, you will be able to start working on your project(s).

<!--

So that you can work with projects cApStAn will provide to you, you must configure your OmegaT installation by adding some additional custom files that we provide separately.

Please follow these steps to proceed with the customization:

+ Download our custom [user configuration bundle](https://github.com/capstanlqc/omegat-user-config/archive/refs/heads/master.zip) to your local disk.

+ Unzip the customization bundle. You should see a list of folders and files like the following:


```
.
├── custo/
├── docs/
├── plugins/
├── scripts/
├── changes.md
├── customisation.properties
├── custom_version.txt
├── files_to_delete.txt
├── filters.xml
├── omegat.autotext
├── omegat.prefs
├── omt-package-config.properties
├── README.md
├── SHA1SUM
├── todo.md
├── uiLayout.xml
└── version_notes.txt
```

+ Run OmegaT and go to **Options** > **Access Configuration Folder**. That will open your Configuration Folder in your file manager.

+ Quit OmegaT.

+ Paste all the folders and files included in the customization bundle in your Configuration Folder.

That's it.
-->

<!--
customization script
![](https://s3.amazonaws.com/media-p.slid.es/uploads/1129410/images/7561590/pasted-from-clipboard.png)
-->

<!--
+ select destination location

![](https://s3.amazonaws.com/media-p.slid.es/uploads/1359547/images/8658907/pasted-from-clipboard.png)

+ select Start Menu folder

![](https://s3.amazonaws.com/media-p.slid.es/uploads/1359547/images/8658914/pasted-from-clipboard.png)

+ Create a desktop shortcut

![](https://s3.amazonaws.com/media-p.slid.es/uploads/1359547/images/8658947/pasted-from-clipboard.png)
-->

<!--
## Further info

### How to uninstall apps on Windows 10

If you're not use how to uninstall an app on Windows 10, the following animation might be helpful:

![](https://media.giphy.com/media/lXYwppV1wwIDOsfLJX/giphy.gif){: style="height:120%;width:120%"}


### 64bit or 32bit machine?

To check whether your computer is 32-bit or 64-bit on Windows 10:

+ Press ++win+e++ to launch the **File Explorer**
+ Right-click on “This PC”
+ Select item “Properties” from the contextual menu
+ In the **System** window, look for “System type”.

See screenshot below:

![](https://media.giphy.com/media/9TZa44h00DErhS7BCo/giphy.gif){: style="height:120%;width:120%"}

-->
