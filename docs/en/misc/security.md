# Security information

OmegaT is the translation tool selected for the language tasks of various projects. cApStAn is responsible for building and customizing this tool so that it can support optimally the translation files that will be prepared for your project, and to streamline language tasks and reduce support requests. 

OmegaT must be installed from a customized installer downloaded from these OmegaT guides. Every user simply must take care of the initial installation and the customization will consist of extensions and tweaked configuration files provided by periodic updates behind the scenes, so as to save users the effort of doing the customization manually.

The purpose of the present document is to provide information relevant for IT departments who must ensure that any software installed in their organization does not pose any security threads. 

## Updating Windows malware definitions

Before downloading the setup files (OmegaT installer and custom configuration script), you may need to update Windows Defender's definitions. On the command prompt as administrator: 

  1. Change directory to `C:\Program Files\Windows Defender`
  1. Run `MpCmdRun.exe -removedefinitions -dynamicsignatures`
  1. Run `MpCmdRun.exe -SignatureUpdate`

Source: [https://www.microsoft.com/en-us/wdsi/definitions](https://www.microsoft.com/en-us/wdsi/definitions)

## Integrity verification

You can check the integrity of the file to make sure that, after download, you have the same file that is available for download in the repository of OmegaT binaries. 

On Windows, you can compute the cryptographic hash values of a binary file with the **File Checksum Integrity Verifier** utility (check [this](https://support.microsoft.com/en-us/help/889768/how-to-compute-the-md5-or-sha-1-cryptographic-hash-values-for-a-file) for further information and download the utility).

The correct hashes of the OmegaT installer can be provided upon request. If you obtain the same values, you can be certain that you have the same file as it’s available for download and that it’s safe to whitelist it.

<!--
- SHA1:	`9a7560368ca11255c4359c2ed225eb0bd7a7fbe0`
- MD5:	`8c4dd481b715396979ba6ec5e2d1e9a8`
These values are taken from the [official OmegaT download page](https://sourceforge.net/projects/omegat/files/OmegaT%20-%20Latest/OmegaT%204.1.5%20update%204/).
--> 

## Java maintenance

OmegaT is developed in Java and needs JRE to run. The OmegaT installers we provide include the version of JRE that OmegaT needs, and that JRE would be uninstalled when OmegaT is uninstalled. Java can be a security risk if it’s not kept up to date, but in this case the Java Runtime Environment is only used by OmegaT, not installed globally, so no maintenance is required.

## Data leakage

OmegaT's git-based team project functionality might be used in the translation projecrt, in which case OmegaT will fetch project files from a private git repository, provided that authentication is correct. Users might have to enter their credentials manually or might receive an authentication file containing hashed credentials.

OmegaT can check for new versions, get MT results, get glossary matches from TaaS, download MediaWiki links and use them as source files, have remote files on HTTP, Git and SVN servers mapped locally, etc. cApStAn does not use any of those functions in translation projects, which means we won't instruct users to configure or use them. 

It’s always possible that the user unilaterally uses them. If this is a concern for the organization, OmegaT could be made to work in a complete offline manner, namely it could be started with a non-functional proxy, so it won't connect to internet at all (specifying a non-existing proxy server, e.g. 270.270, in the startup parameters in the `OmegaT.l4J.ini` file). In other words, it’s up to the organization and their internal policy to decide how much access to the internet it must be allowed to OmegaT.

However, if team projects are used but the has an offline policy, the user will not benefit from certain features of team projects: download new files on the fly, commit target files directly to the live preview, etc.

## Open source

In case of any concerns about vulnerabilities in OmegaT against viruses or other malware, the source code used to build software packages for the several OS distributionsis is available [here](https://github.com/capstanlqc/omegat). Any Java engineer can inspect the code and conduct any tests to assess its robustness and reliability.

## Endorsement by big organizations

The European Commission has been promoting the use of open-source software namely within its [R&D programmes]. It is in this context that open source applications like OmegaT are being used in DGT (the European Commission’s Directorate-General for Translation), alongside other commercial applications. DGT has been using OmegaT for prototyping since 2012, customizing it and extending it with some useful improvements. This information can be useful to endorse the usage of OmegaT. Source: [http://ec.europa.eu/translation/portuguese/magazine/documents/folha54_ot_en.pdf](http://ec.europa.eu/translation/portuguese/magazine/documents/folha54_ot_en.pdf)

OmegaT is also one of the Translator Partners of Microsoft. Please see [https://www.microsoft.com/en-us/translator/business/partners/](https://www.microsoft.com/en-us/translator/business/partners/). 

DGT and Microsoft can attest the security of OmegaT.

