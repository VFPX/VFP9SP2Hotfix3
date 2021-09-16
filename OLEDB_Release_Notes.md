# Microsoft OLE DB Provider for Visual FoxPro 9.0

The Visual FoxPro OLE DB Provider (VfpOleDB.dll) exposes OLE DB interfaces that you can use to access Visual FoxPro databases and tables from other programming languages and applications. 

## Microsoft Release Notes
Source: https://web.archive.org/web/20190108160318/https://www.microsoft.com/en-us/download/details.aspx?id=14839

## Details

**Note**: There are multiple files available for this download. 

Version: 1.2

Date Published: 5/16/2008
- [VFPOLEDBSetup.msi](VFPOLEDBSetup.msi) (1.2 MB) - VFP OLE DB Provider Installer.
- [vfpoledb.msm](vfpoledb.msm) (829 KB) - VFP OLE DB Merge Module.

The Visual FoxPro OLE DB Provider (VfpOleDB.dll) exposes OLE DB interfaces that you can use to access Visual FoxPro databases and tables from other programming languages and applications. The Visual FoxPro OLE DB Provider is supported by OLE DB System Components as provided by MDAC 2.6 or later. The requirements to run the Visual FoxPro OLE DB Provider are the same as for Visual FoxPro 9.0.

**Note: This version of the VFP OLE DB provider is the same version as the one included with Visual FoxPro 9.0 SP2.**

## System Requirements

**Supported Operating System**

    Windows 2000 Service Pack 3, Windows 98, Windows ME, Windows Server 2003, Windows XP
    Processor: Pentium class
    RAM: 64 MB (recommended: 128 MB or higher)
    Available Hard Disk Space: 2 MB for minimum install, 4 MB for full install
    Software Microsoft Data Access Components (MDAC) version 2.6 or higher
    Note: Installation on Windows NT 4.0 is not supported. 

## Install Instructions

Important download details: Installing the Microsoft OLE DB Provider for Visual FoxPro 9.0 on a computer that has a previous version of the Provider causes this version to replace the previous version. If you wish to preserve the previous version of the Provider, you must rename it before proceeding with this installation. To rename the Provider using Windows Explorer:

Shut down any applications that might be using the provider, such as IIS, or any desktop applications that use the provider.

Open the ...\Program Files\Common Files\System\Ole DB folder

Right-click vfpoledb.dll, select Rename, and then change the name to vfpoledb_save.dll

To restore the saved version, delete or rename this release version, and rename vfpoledb_save.dll to vfpoledb.dll. It should not be necessary to re-register the provider, provided that you have not uninstalled the previous version. 

## Additional Information

Refer to Microsoft OLE DB Provider for Visual FoxPro 9.0 Readme included for additional information. 