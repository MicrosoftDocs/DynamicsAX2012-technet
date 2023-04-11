---
title: (RUS) Create a corrective document
TOCTitle: (RUS) Create a corrective document
ms:assetid: 30280655-3038-4b29-832a-f52cee7b3762
ms:mtpsurl: https://technet.microsoft.com/library/JJ677497(v=AX.60)
ms:contentKeyID: 49384801
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- document
- correct
- correction document
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a corrective document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a corrective document to correct a document that is returned by the tax authority because it is incomplete or incorrect. You can also maintain the original document. The correction document is differentiated from the original document by the document type value that is specified in the **Document type:** field on the **General** tab in the **Documents** form. In the original document, the document type value is 1 for documents in text format, and 0 for documents in XML format. In the corrective document, the document type value is 1 for documents in text format, and 1/999 for documents in XML format.

1.  Click **General ledger** \> **Reports** \> **External** \> **Electronic documents list**.

2.  Select a document that has a status of **Finished**, and then click **Functions** \> **Create correction**.

3.  In the **Corrective document** field, enter a code for the document.

4.  In the **Description** field, update the description for the document.

5.  Click **OK**. A line is created in the **Documents** form with the document code and a status of **Received**.

6.  Click the **General** tab, and then in the **Corrective number** field, verify the version number for the correction that was made to the original document.

7.  Click **Status** \> **Approved** to change the status of the document to **Approved**.

8.  Click **Export to**, and then in the **Directory** field, enter the path where the text file is saved.

9.  In the **File name** field, enter the name of the text file, and then click **OK**.

10. After you submit the document to the tax authority, click **Status** \> **Finished**. The status of the document is updated to **Finished**.

## See also

[(RUS) Export an electronic reporting document](rus-export-an-electronic-reporting-document.md)

[(RUS) Documents (form)](https://technet.microsoft.com/library/jj852139\(v=ax.60\))

[(RUS) Create correction (form)](https://technet.microsoft.com/library/jj710782\(v=ax.60\))

[(RUS) Import data from the Financial reports generator report](rus-import-data-from-the-financial-reports-generator-report.md)

  


