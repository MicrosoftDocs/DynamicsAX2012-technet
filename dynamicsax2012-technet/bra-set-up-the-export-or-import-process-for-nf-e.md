---
title: (BRA) Set up the export or import process for NF-e
TOCTitle: (BRA) Set up the export or import process for NF-e
ms:assetid: fa7fd30c-9ee8-49e1-a7ac-f072d7253cb7
ms:mtpsurl: https://technet.microsoft.com/library/JJ933539(v=AX.60)
ms:contentKeyID: 50935153
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- NF-e
- electronic fiscal document
- export process
- import process
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the export or import process for NF-e 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to set up the export or import process for a Nota Fiscal eletrônica (NF-e), so that you can generate or receive XML messages.

1.  Click **System administration** \> **Setup** \> **Batch group**.

2.  Create a batch group for the NF-e process. For more information, see [Create a batch group](create-a-batch-group.md).

3.  Click **Accounts receivable** \> **Periodic** \> **NF-e Federal** \> **Export/import NF-e process**.

4.  Select the **Batch processing** check box to run the task as a batch job.

5.  In the **Task description** field, enter or update the description of the export or import process.

6.  In the **Batch group** field, select the batch group that you created to attach that batch group to the batch job.

7.  Select the **Private** check box to indicate that the export process can be run only by the user who selected the process.

8.  Click **Recurrence** to open the **Recurrence** form.

9.  Set up a recurrence for the batch job, and then click **OK**.

10. In the **Export/import NF-e process** dialog box, click **OK** to set up the export or import process for an NF-e.

## See also

[Batch groups (form)](https://technet.microsoft.com/library/aa575384\(v=ax.60\))

[Recurrence (form)](https://technet.microsoft.com/library/aa616143\(v=ax.60\))

  


