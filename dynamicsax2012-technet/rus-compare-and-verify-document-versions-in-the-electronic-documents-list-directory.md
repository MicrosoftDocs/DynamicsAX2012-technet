---
title: (RUS) Compare and verify document versions in the Electronic documents list directory
TOCTitle: (RUS) Compare and verify document versions in the Electronic documents list directory
ms:assetid: ce7af2ff-1313-4c80-8413-0431003c9b39
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677804(v=AX.60)
ms:contentKeyID: 49385004
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- compare
- documents
- electronic reporting
---

# (RUS) Compare and verify document versions in the Electronic documents list directory [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Each document that is stored in the electronic documents list directory can have an unlimited number of versions. The versions are saved in hierarchical order. The differences in document versions occur based on the way in which they are created.

1.  Click **General ledger** \> **Reports** \> **External** \> **Electronic documents list**.

2.  Select a document that has a status of **Received**, **Approved**, or **Finished**, and then click **View**. The Microsoft Excel worksheet is opened on the **Document** tab.

3.  Click **Functions** \> **Compare**.

4.  Select the versions to compare from the list or from the version tree, and then click **OK**. On the **Requisites** tab, you can view a list of the differences between the values of the requisites. On the **Document** tab, you can view the compared values and the numeric differences that are highlighted, with comments.

5.  Click **Functions** \> **Check** to verify that the structure of the sections and requisites correspond with the structure of the appropriate document template, and that the requisite values correspond with the extended data types in the settings. Discrepancies in the structure and requisites are displayed in a **Dialog** form.
    
    On the **Requisites** tab, you can review a list of requisites that do not meet the conditions of the specified extended data types, or instances where an extended data type is not set.
    

    > [!NOTE]
    > <P>In the <STRONG>Show</STRONG> field, select <STRONG>With errors</STRONG>. On the <STRONG>Document</STRONG> tab, you can view the comments. The error message is displayed as a note.</P>



## See also

[(RUS) Documents (form)](https://technet.microsoft.com/en-us/library/jj852139\(v=ax.60\))

[(RUS) Version (form)](https://technet.microsoft.com/en-us/library/jj710759\(v=ax.60\))

[(RUS) Select version (form)](https://technet.microsoft.com/en-us/library/jj710679\(v=ax.60\))

[(RUS) Update an electronic reporting document](rus-update-an-electronic-reporting-document.md)

[(RUS) View, reverse, or print electronic reporting documents](rus-view-reverse-or-print-electronic-reporting-documents.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

