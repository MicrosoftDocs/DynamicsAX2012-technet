---
title: Preserve legacy element IDs
TOCTitle: Preserve legacy element IDs
ms:assetid: 74c2ed30-1b6c-48b1-bed3-4d849abf2243
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733496(v=AX.60)
ms:contentKeyID: 49685457
ms.date: 06/17/2014
mtps_version: v=AX.60
---

# Preserve legacy element IDs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 4.0 and Microsoft Dynamics AX 2009, objects from multiple solutions in the product could possess the same object ID. Either the solutions were not installed together, and thus were not in conflict, or they were installed together and then merged manually by an ISV to avoid any ID conflict. However, as of Microsoft Dynamics AX 2012 R2, Microsoft merged PI (process manufacturing production and logistics), SI (project management and accounting), GLS (country/region-specific features), and Retail into the SYS layer. Consequently, IDs must be unique across all Microsoft metadata. If you have any of these solutions installed on your legacy system, you must identify the legacy object IDs during upgrade and preserve the ID references embedded in your business data.

The following is an overview of the process for preserving legacy element IDs:

1.  ISV partners: Create any additional required rename files for your solution, and provide them to customers to run on their target systems.

2.  Run a job on the source system that analyzes legacy IDs in both the code and the business data, and then generates a text file. If you are upgrading to Microsoft Dynamics AX 2012 R3, you can do this by running the **Export baseline element IDs** checklist task. For information, see [Export baseline element IDs](export-baseline-element-ids.md). If you are upgrading to Microsoft Dynamics AX 2012 R2 or R3, follow the instructions below in the section “Capture and preserve legacy IDs (Customers).”

3.  Manually copy the text file to the target system.

4.  Copy the default rename file from the installation media to the target system, as well as any ISV partner rename files provided for the solutions that you are running.

5.  Run the **Preserve legacy element IDs** task in the **Code upgrade checklist**. As part of this job, the upgrade framework makes the target system’s object IDs match the legacy IDs.


> [!IMPORTANT]
> <P><STRONG>Source system requirements</STRONG> Do not install the upgrade preprocessing XPOs on your source system until after you have preserved the legacy object IDs. If the XPO files have already been installed, restore your application folders with a backup taken before you installed the files.</P>
> <P>It is important to preserve legacy IDs before you install the upgrade framework XPOs because you do not want to capture the upgrade framework object IDs along with the legacy IDs.</P>
> <P><STRONG>Target system requirements</STRONG> The target system AOS and database must be running on the same computer.</P>



## Create required rename files (ISV Partners only)

If you are an ISV partner, and you have renamed metadata elements, you must create a rename mapping file to distribute to your customers along with your model files.

1.  To find the information for the rename file, we recommend that you compare elements from your legacy solution with elements from your Microsoft Dynamics AX 2012 R2 or R3 solution, and ensure that you identify those that have different names and IDs.
    
    Strategies for finding renamed elements include:
    
      - Import the existing AOD files from your legacy solution into the baseline database, and then run a SQL query between the baseline database and the target database.
    
      - Export the AOD files from your legacy solution to Microsoft Excel, and the files from your solution that runs on the current version of Microsoft Dynamics AX to Excel.

2.  Run the following types of comparisons between your legacy solution and current-version solution to identify objects that have been renamed. Find elements that have the following characteristics:
    
      - The same IDs but different names
    
      - The same names but different IDs

3.  Create a comma-separated value (CSV) file that contains information about all the renamed elements that you have found. Use the following format:
    
    Element type (integer), element name, new element name, new parent element name

## Capture and preserve legacy IDs (Customers)

If you are upgrading to Microsoft Dynamics AX 2012 R2 or R3, perform the **Preserve legacy element IDs** task by completing the steps that follow. If you are upgrading to Microsoft Dynamics AX 2012 R3, use the **Export baseline element IDs** checklist task to capture your legacy element IDs and skip to step 4.

1.  (On the installation media, locate the file PrivateProject\_SysUpgradeExportIdMap.xpo in the DatabaseUpgrade\\XPO folder. Copy the file to the source system.

2.  Import PrivateProject\_SysUpgradeExportIdMap.xpo. For information about importing XPO files during upgrade, see [Install upgrade framework files](install-upgrade-framework-files.md) and [Install optional upgrade XPO files](install-optional-upgrade-xpo-files.md).

3.  In **Project** \> **Private**, locate the SYSUpgradePreserveID job, right-click it, and click **Open**. The output of the job will be saved as \<drive\>:\\Users\\\<username\>\\AppData\\Local\\Temp\\1\\SysUpgradeExportIdMap.csv. An Infolog window will open when the job is finished.

4.  Create or identify a temporary file share on the target system that the SQL Server service account has permission to write to.

5.  Copy the file **SysUpgradeExportIdMap.csv** to the file share on the target system.

6.  Retrieve the file DatabaseUpgrade\\XPO\\MicrosoftElementsRenamed62.csv from the installation media, and copy it to the same location on the target system.

7.  Copy any additional rename files that are required for the ISV solutions that you are running to the same location on the target system.

8.  When you are ready to perform the **Preserve legacy element IDs** task, stop the target system AOS.

9.  Open a Microsoft Dynamics AX 2012 Management Shell window, and execute the following command.
    
        axutil idkeep /idfile:filename /renamefile:filename1, filename2, filename3 /verbose
    
    The idfile:filename parameter contains the path and file name of SysUpgradeExportIdMap.csv.
    
    The /renamefile parameter contains the path and file name of MicrosoftElementsRenamed62.csv. There may be additional rename files because of the presence of ISV solutions.
    
    For example, if there are no additional ISV rename files, the command is as follows.
    
        axutil idkeep /idfile:C:\temp\SysUpgradeExportIdMap.csv /renamefile:c:\temp\MicrosoftElementsRenamed62.csv /verbose

10. Stop the AOS and compile the application using AxBuild.exe. For information, see [AxBuild.exe for Parallel Compile on AOS of X++ to p-code](https://technet.microsoft.com/en-us/library/dn528954\(v=ax.60\)).

11. Restart the AOS, open the client, and continue with the next checklist task.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

