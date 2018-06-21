---
title: (RUS) Import data from the Financial reports generator report
TOCTitle: (RUS) Import data from the Financial reports generator report
ms:assetid: 62641a57-ad64-4f6d-8762-03364c460c78
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677548(v=AX.60)
ms:contentKeyID: 49384852
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- import
- import data
- FRG
---

# (RUS) Import data from the Financial reports generator report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The electronic documents list directory is used to store all reports that are submitted electronically to the tax authorities. A tax document can have an unlimited number of versions. However, only the active version is processed when you use the document view and export functions.

You can import report data from a file, from the Financial reports generator (FRG) report, or from an earlier version of the document.

1.  Click **General ledger** \> **Reports** \> **External** \> **Electronic documents list**.

2.  In the **Template** field, select a document template.

3.  Click **New** to create a line.

4.  In the **Description** field, enter a description for the document.

5.  In the **Period start** and **Period ends** fields, select the starting and ending dates of the reporting period.

6.  In the **Sender** field, select the name of the employee who sends the document.

7.  To import data from an external Microsoft Excel file, click **Load** \> **File**.
    

    > [!NOTE]
    > <P>The <STRONG>Load</STRONG> button is available only for documents that have a status of <STRONG>Created</STRONG> or <STRONG>Received</STRONG>.</P>



8.  In the **File name** field, enter the name and path of the Excel file.

9.  In the **Note line** field, enter a description for the file, and then click **OK**.

10. To import data for reports that are created by the FRG, click **Load** \> **Report**.

11. In the **Note line** field, enter a description for the report, and then click **OK**.

12. To import data from an earlier version of the document, click **Load** \> **Version**.

13. In the **Current version** field, select the current version of the document.

14. In the **Note line** field, update the description for the current document, and then click **OK**.

15. On the **General** tab, in the **Current version** field, select the current version of the document.

16. Click **Requisites** to view the report data.
    

    > [!NOTE]
    > <P>The <STRONG>Requisites</STRONG> button is available only for documents that have a status of <STRONG>Received</STRONG>.</P>



## See also

[(RUS) Documents (form)](https://technet.microsoft.com/en-us/library/jj852139\(v=ax.60\))

[(RUS) Versions (form)](https://technet.microsoft.com/en-us/library/jj710762\(v=ax.60\))

[(RUS) Load version (form)](https://technet.microsoft.com/en-us/library/jj710716\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

