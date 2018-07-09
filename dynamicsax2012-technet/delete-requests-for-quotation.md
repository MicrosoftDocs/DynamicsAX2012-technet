---
title: Delete requests for quotation
TOCTitle: Delete requests for quotation
ms:assetid: 8c4f5102-4896-4348-82e0-f4de26ea7f7e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242868(v=AX.60)
ms:contentKeyID: 36058481
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- Classes.PurchRFQCleanUp
- RFQ
- procurement
- request for quotation
- requests for quotations
- quote
- request for quotations
- requests for quotation
- RFQs
- deletion
- deletions
---

# Delete requests for quotation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can delete requests for quotation (RFQs) and RFQ replies from Microsoft Dynamics AX 2012 R3. The corresponding RFQ journals are not deleted, but remain as a record in the system.

## Delete a request for quotation

Use this procedure to delete a single request for quotation. You can do this only if you have not sent the RFQ yet. The highest status on all lines in the RFQ must be **Created**.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Open the RFQ that you want to delete.

3.  On the **Action Pane**, click **Delete**.

## Delete a group of requests for quotation

Use this procedure to clean up AX 2012 R3 by deleting old RFQs and the corresponding replies that you no longer need.

1.  Click **Procurement and sourcing** \> **Periodic** \> **Clean up** \> **Delete requests for quotations**.

2.  Click the **Batch** tab.

3.  Set the criteria for which RFQs to delete. For example, this can be all RFQs created before a specific date, or all RFQs that expired on a specific date/time.

For more information, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

## See also

[About request for quotation statuses](about-request-for-quotation-statuses.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

