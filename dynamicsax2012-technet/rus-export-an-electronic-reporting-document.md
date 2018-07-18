---
title: (RUS) Export an electronic reporting document
TOCTitle: (RUS) Export an electronic reporting document
ms:assetid: 907fde6c-61be-4da4-a461-4536c92b3497
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677609(v=AX.60)
ms:contentKeyID: 49384918
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- document
- template
- export
- electronic reporting
audience: Application User
ms.search.region: Russia
---

# (RUS) Export an electronic reporting document 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must export a reporting document to create a text file to submit to the tax authorities. Only the current version of the file is exported. The export format and file naming rules for the document are detected automatically.

1.  Click **General ledger** \> **Reports** \> **External** \> **Electronic documents list**.

2.  Import data from a file, report, or version. For more information, see [(RUS) Import data from the Financial reports generator report](rus-import-data-from-the-financial-reports-generator-report.md).

3.  Select a document that has a status of **Received**, and then click **Status** \> **Approved**. The status of the document is updated to **Approved**.

4.  Click **Export to**, and then in the **Directory** field, enter the path where the text file is saved.

5.  In the **File name** field, enter the name of the text file, and then click **OK**.

6.  After you submit the document, click **Status** \> **Finished**. The status of the document is updated to **Finished**. To update a document that has a **Finished** status, you must create a correction document. For more information, see [(RUS) Create a corrective document](rus-create-a-corrective-document.md).

7.  To correct the document before you submit it, click **Status** \> **Reset** to change the document status to **Received**.
    

    > [!NOTE]
    > <P>Each time that you reset the status, the document reverts to its previous status. For example, if the document status is <STRONG>Finished</STRONG>, it is reset to <STRONG>Approved</STRONG>. If you click <STRONG>Status</STRONG> &gt; <STRONG>Reset</STRONG> again, the status is updated to <STRONG>Received</STRONG>.</P>



## See also

[(RUS) Documents (form)](https://technet.microsoft.com/en-us/library/jj852139\(v=ax.60\))

  


