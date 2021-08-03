# VFP 9 Service Pack 2 (SP2) and Hotfix 3

This repository contains updates to Visual FoxPro Version 9 (VFP9). Use the `VERSION()` command to assess your current version of VFP.

The **latest fully patched version of VFP9** is

```
Visual FoxPro 09.00.0000.7423 for Windows
```

If your version is `09.00.0000.2412` then you don't have any service packs installed.

To upgrade VFP9 to the latest service pack and hotfix, follow these steps.

## Step 1: Upgrade VFP9 to Service Pack 2

If your version is `09.00.0000.5815` then you already have Service Pack 2 installed.  You can skip to the next step to install the latest hotfix.

Execute the file `VFP9_sp2.exe` to update the original release of VFP9 to Service Pack 2.

The file `VFP9SP2_BugFixList.htm` lists the changes in SP2.

##  Step 2: Upgrade VFP9 SP2 to Hotfix 3 (the Latest Hotfix)

Execute `VFP90SP2-KB968409-ENU.exe` to extract files into a folder you will subsequently specify. Follow the instructions in the readme (in that folder) to copy the files to their correct locations.

## Other Things

* Execute `VFPODBC.msi` to get the latest VFP ODBC driver.
* Execute `HTMLHelp.exe` to install the Microsoft HTML Help Workshop (needed to build CHM files).
* Execute `VFPOLEDBSetup.msi` to get the latest VFP OLE DB provider.

## More Info

See wOOdy's blog entry ["How to install VFP9 in a modern world"](http://woody-prolib.blogspot.com/2018/12/how-to.html) for more details and tips on how to set up VFP9 and upgrade to the latest version.

