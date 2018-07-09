---
title: Update the expiration date for an inventory batch
TOCTitle: Update the expiration date for an inventory batch
ms:assetid: 3a1763be-e1a0-420b-8fc9-0305c6ac807e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352196(v=AX.60)
ms:contentKeyID: 36687829
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Update the expiration date for an inventory batch [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to update the expiration date for one or more inventory batches.

1.  Click **Inventory management** \> **Periodic** \> **Batches** \> **Update expiry dates**.

2.  In the **Data calculation type** field, select the applicable type to update this field.
    
      - **System** ─ The system calculates the expiration date. If you specify the **Shelf life period in days** in the **Released product details** form, the system calculates the expiration date as follows: **Production date of batch + Shelf life period in days**.
    
      - **Fixed** ─ Select the new expiration date in the **Expiration date** field.

3.  Click **Select** to enter selection criterion to locate the inventory batches that you want to include in the batch job.

4.  Click **Batch** to enter the batch criterion to run a job to update the expiration dates of the inventory batches that you select.

5.  Click **OK** to run the batch job.

## See also

[(PM) Released product details (form)](https://technet.microsoft.com/en-us/library/hh352306\(v=ax.60\))

[Update expiry dates (form)](https://technet.microsoft.com/en-us/library/hh227601\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

