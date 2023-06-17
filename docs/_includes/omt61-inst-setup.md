<!-- #  OmegaT 6.1.0 installation and setup guide -->
#  OmegaT 6.1.0 installation and setup guide

OmegaT is the open source computer-assisted translation tool (CAT tool) which we use to translate, reconcile, adapt, review and verify materials. You must install OmegaT and set it up with some additional files, in order to ensure an optimal interface and compatibility with the project we'll prepare for you.

> In particular, OmegaT 6.1 is necessary to work with Myanmar languages.

## OmegaT version

Please: 

+ Download OmegaT 6.1.0 from the **link provided** in this guide. Do not download OmegaT from another link.
+ Install OmegaT version 6.1.0 (from the link in this guide). Do not install **any other** version of OmegaT.

## Installation and setup

Notice that there are two steps in the installation process:

1. Installation of OmegaT
2. Installation setup

A setup update doesn't require re-installing OmegaT.

If OmegaT is already installed in your machine but it's not version 6.1.0, please uninstall that version before proceeding. You can check OmegaT's version in the title bar.

![](https://s3.amazonaws.com/media-p.slid.es/uploads/1129410/images/9336800/pasted-from-clipboard.png)

<!-- Check the [¶ How to uninstall apps on Windows 10](#how-to-uninstall-apps-on-windows-10) section below if you're not sure how to proceed. -->

> If OmegaT 6.1.0 is already installed in your machine, you may skip this section and go straight to the [1.3. Install the customization files](#13-install-the-customization-files) section below to proceed with the customization.

### 1.1. Download installer

<!-- Please download the OmegaT 6.1 installer from [here](https://nextcloud.capstan.be/index.php/s/8o4njsQszczNG7F). -->

Please download the OmegaT 6.1 installer from [here](https://nextcloud.capstan.be/index.php/s/PM9iQGRJFZbAfYP). 



> You must have a 64-bit machine to install this version of OmegaT. If that's not the case, please get in touch with our Helpdesk. <!-- Check the [¶ 64bit or 32bit machine?](#64bit-or-32bit-machine) section below if you're not sure how to check whether you have a 64-bit or 32-bit machine. -->

It's a safe download, even if your browser might not trust the file.

### 1.2. Install OmegaT

In order to proceed with the installation, please follow these steps: 

+ Double click the `OmegaT_6.1.0_Beta_Windows_64.exe` file that you have downloaded.

+ Choose (or keep) English as the language of the installation:

    ![](https://s3.amazonaws.com/media-p.slid.es/uploads/1359547/images/8658891/pasted-from-clipboard.png)
    <!-- {: style="height:50%;width:50%"} -->

+ Please also use English as the language of the OmegaT user interface:

    ![](https://s3.amazonaws.com/media-p.slid.es/uploads/1359547/images/8658900/pasted-from-clipboard.png)<!-- {: style="height:70%;width:70%"} -->

+ In the License Agreement screen, please select "I accept the agreement” and click “Next”:

    ![](https://s3.amazonaws.com/media-p.slid.es/uploads/1359547/images/8658905/pasted-from-clipboard.png)<!-- {: style="height:70%;width:70%"} -->

+ In all other dialogs, just press “Next” to use the default options until you reach the “Ready to Install” screen.

+ Then click on “Install”.

    ![](https://s3.amazonaws.com/media-p.slid.es/uploads/1359547/images/8658919/pasted-from-clipboard.png)<!-- {: style="height:70%;width:70%"} -->

### 1.3. Install the customization files

So that you can work with projects cApStAn will provide to you, you must customize your OmegaT installation by adding some additional setup files that we provide separately.

Please follow these steps to proceed with the customization: 

+ Download the [customization bundle](https://github.com/capstanlqc/omegat-customization/archive/refs/heads/master.zip) to your local disk.

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
