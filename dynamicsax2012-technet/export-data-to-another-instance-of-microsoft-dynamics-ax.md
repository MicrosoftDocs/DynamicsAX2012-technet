---
title: Export data to another instance of Microsoft Dynamics AX
TOCTitle: Export data to another instance of Microsoft Dynamics AX
ms:assetid: 117863f3-33b4-4bf9-9427-7c886a258be3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309596(v=AX.60)
ms:contentKeyID: 35132551
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Export data to another instance of Microsoft Dynamics AX [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the export operation in Microsoft Dynamics AX to export a subset of data from a single company. You can then import the data to another company. This company can be in the same partition, in a different partition, or in a partition in another instance of Microsoft Dynamics AX.

Before you read this topic, we strongly recommend that you read the information in [Plan data import, export, and migration](plan-data-import-export-and-migration.md).

The export and import functionality in Microsoft Dynamics AX is designed to export and import tables in individual companies. The doInsert, doUpdate, and doDelete methods that are called by the export and import functionality cannot be overwritten. Therefore, any application logic that is written at the table level is not called during export and import operations.

Before you begin, make sure that the current partition and company account are the partition and account that you want to export data from.

For more information about how export operations are processed, see [Use DAT and DEF files to export and import data](use-dat-and-def-files-to-export-and-import-data.md).

## Reliability and performance

Data export is a resource-intensive activity—it requires significant database, memory, and processing.

Consider the following recommendations before you begin an export operation:

  - Back up the source data before you perform an export.

  - Perform all exports outside core working hours.

## Export data

1.  Click **System administration** \> **Common** \> **Data export/import** \> **Export to**.

2.  On the **General** tab, select the definition group that you want to export.

3.  Enter the name of the file that you want to export the data to.
    

    > [!NOTE]
    > <P>Do not include periods in file names, except between the name and the extension. File names that include periods are not supported for export files.</P>



4.  Select the type of file that you are exporting the data to:
    
      - **Binary** – Data is exported as a compressed file format. This option is most frequently used.
    
      - **Comma** – Data is exported as a comma-separated value (CSV) list.
        

        > [!WARNING]
        > <P>When you export data as a CSV list, some data is omitted, such as container fields, line breaks, and binary data.</P>



5.  If you must run the export operation immediately, select the **Execute on AOS** check box.
    
    Typically, selecting this option improves performance.

6.  To schedule the export operation as a batch job, use the **Batch** tab to select a batch that runs on the schedule you prefer.

## See also

[Import data from another instance of Microsoft Dynamics AX](import-data-from-another-instance-of-microsoft-dynamics-ax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

