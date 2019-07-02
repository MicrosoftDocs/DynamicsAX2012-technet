---
title: Install upgrade framework files
TOCTitle: Install upgrade framework files
ms:assetid: de8bf5a7-4ae0-498c-82cc-8423b67e045d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg732154(v=AX.60)
ms:contentKeyID: 35133096
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install upgrade framework files 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

The Microsoft Dynamics AX 2012 upgrade process requires manual installation of three files on your source Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 system. An XPO file provides the forms and scripts that are required for data preprocessing, an ALD file provides user interface labels, and a CHM file provides user Help. The sections below describe how to install these files from your Microsoft Dynamics AX 2012 installation media.

## Install and import the XPO upgrade framework file

The preprocessing XPO file installs an upgrade framework containing the following components:

  - The **Preprocessing upgrade checklist**

  - The user-input forms opened by the items in the checklist

  - The preprocessing upgrade scripts

  - Changes to the upgrade cockpit for upgrade readiness, live preprocessing, live delta preprocessing, and final preprocessing in single-user mode

You will import the preprocessing XPO into the USR layer on the Microsoft Dynamics AX source system. You can see the current application layer in the lower right of the Microsoft Dynamics AX client window.


> [!NOTE]
> <P>If the current application layer is not the USR layer, you must exit Microsoft Dynamics AX and then create or modify the configuration by using the <STRONG>Microsoft Dynamics AX Configuration Utility</STRONG>. In Microsoft Dynamics AX 4.0, the path is <STRONG>Start</STRONG> &gt; <STRONG>Administrative Tools</STRONG> &gt; <STRONG>Microsoft Dynamics AX Configuration Utility</STRONG>. In Microsoft Dynamics AX 2009, the path is <STRONG>Start</STRONG> &gt; <STRONG>Administrative Tools</STRONG> &gt; <STRONG>Microsoft Dynamics AX 2009 Configuration</STRONG>. Reconfigure the client so that it opens in the USR layer.</P>



Be sure to back up your application files (\*.aod) and label files (\*.ald) before you import the preprocessing XPO. You will need these files for code upgrade on the Microsoft Dynamics AX 2012 target system.


> [!IMPORTANT]
> <P>If you are upgrading to Microsoft Dynamics AX 2012 R2, you may need to preserve legacy element IDs before you install the upgrade framework file. For more details, see <A href="preserve-legacy-element-ids.md">Preserve legacy element IDs</A>.</P>



To retrieve the preprocessing XPO, download the most recent Cumulative Update available of the Microsoft Dynamics AX 2012 version you are targeting.

To install the preprocessing XPO on the Microsoft Dynamics AX source system, do the following:

1.  Open the Application Object Tree (AOT) from its icon on the toolbar.

2.  (Optional.) It is advisable to make sure that the Application Object Directory (AOD) is synchronized with the Microsoft Dynamics AX database schema before you begin to import of the XPO. Synchronize them as follows:
    
      - Right-click **Data Dictionary**, and then click **Synchronize**.
    
    Synchronization may take several minutes.

3.  Click the import icon on the AOT menu bar.

4.  In the **Import** dialog box, click **Browse**. The XPO is located in the DatabaseUpgrade\\XPO folder of the Microsoft Dynamics AX 2012 Cumulative Update you downloaded earlier. The XPO file that you import depends on the Microsoft Dynamics AX source system that you are upgrading from.
    
      - On a Microsoft Dynamics AX 4.0 source system, import UpgradeAX4.xpo.
    
      - On a Microsoft Dynamics AX 2009 source system, import UpgradeAX5.xpo.

5.  In the **Import** dialog box, make sure that the option **Import with ID values** is cleared.

6.  Click **OK**.

7.  In the **Import** message box, click **Yes to all** when you are prompted to continue the import.

8.  During synchronization, the **Problems during synchronization** message box may warn you that tables will be dropped. You should be aware of what objects are being over-written so that you can stop the process if necessary and merge your custom code with the XPO code for objects common to them both. To allow an object to be overwritten, click **Yes**.

Microsoft Dynamics AX 2009 automatically performs multiple compilation passes to make sure that validation is successful. For example, if a child object in the code is validated before its parent object, the system will display a compilation error, but in a subsequent compilation pass, the parent-child object relationship will be established and the error will no longer be displayed.

Microsoft Dynamics AX 4.0 does not automatically perform multiple compilation passes. If you import the preprocessing XPO into Microsoft Dynamics AX 4.0, you may have to manually recompile the application until no compilation errors are returned.


> [!IMPORTANT]
> <P>The framework XPO for Microsoft Dynamics AX 2009 modifies the index of the production-system table Batch.Statuser in order to optimize performance during data preprocessing.</P>



## Install the ALD label file

The ALD file contains the labels that appear in the upgrade framework user interface. The **Preprocessing upgrade checklist** and associated forms will not be displayed properly without this file. To install the ALD file, do the following:

1.  On your installation media, navigate to the folder DatabaseUpgrade\\ALD folder and locate the ALD label file that you plan to use. Your choice will depend on the default language that you want to install. For example, the file axUPGen-us.ald provides labels in United States English for the upgrade framework forms. Each language and language region that is supported by Microsoft Dynamics AX has its own ALD file.

2.  Copy axUPGen-us.ald (or other selected ALD file) to the label folder on your source system.
    
      - On a typical Microsoft Dynamics AX 4.0 system, copy the file to C:\\Program Files (x86)\\Microsoft Dynamics AX\\40\\Application\\Appl\\Standard\\.
    
      - On a typical Microsoft Dynamics AX 2009 system, copy the file to C:\\Program Files\\Microsoft Dynamics AX\\50\\Application\\Appl\\Standard\\.

3.  Restart the application object server.

## Install the CHM file for user Help

The CHM file provides the documentation that opens when you click **Help** next to an item on the **Preprocessing upgrade checklist**. To install the CHM file, do the following:

1.  Locate the file UpgradePreprocessing.chm in the DatabaseUpgrade\\CHM folder on your installation media.

2.  Copy the file to the appropriate directory on your Microsoft Dynamics AX source system.
    
      - On a Microsoft Dynamics AX 4.0 system, copy the file to C:\\Program Files\\Microsoft Dynamics AX\\40\\Client\\Bin\\Help\\EN-US\\.
    
      - On a Microsoft Dynamics AX 2009 system, copy the file to C:\\Program Files\\Microsoft Dynamics AX\\50\\Client\\Bin\\Help\\EN-US\\.

## Other upgrade scripts and documentation

Microsoft Dynamics AX has other upgrade scripts that are different than those documented in UpgradePreprocessing.chm.

These other upgrade scripts include X++ code that maps data between the source and target database schemas. They include preprocessing scripts run on the source system in preparation for data upgrade. They also include target scripts run on the target system during data upgrade.


> [!TIP]
> <P>Help topics that document most of these other upgrade scripts can be found on the MSDN website. To view the table of contents for these topics, search MSDN for the phrase <STRONG>Data Upgrade Scripts for Microsoft Dynamics AX</STRONG>.</P>


  


