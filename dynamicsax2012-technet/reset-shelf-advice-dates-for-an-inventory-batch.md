---
title: Reset shelf advice dates for an inventory batch
TOCTitle: Reset shelf advice dates for an inventory batch
ms:assetid: 9c173694-930c-498e-87fc-409505d87f10
ms:mtpsurl: https://technet.microsoft.com/library/Hh352308(v=AX.60)
ms:contentKeyID: 36687937
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reset shelf advice date for single batch
- shelf advice date
- update shelf advice date for multiple batches
audience: Application User
ms.search.region: Global
---

# Reset shelf advice dates for an inventory batch 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to reset the shelf advice date for a single inventory batch or multiple inventory batches. This date identifies the date when a batch or lot should be retested to validate that it still meets testing standards.

## Update a single inventory batch

1.  Click **Inventory management** \> **Inquiries** \> **Batches** \> **Shelf advice as of date**.

2.  Click **Functions** and select **Reset shelf advice date**. The **Reset shelf advice date for selected batch** dialog box is displayed.

3.  In the **Shelf advice date** field, select the new date.

4.  Click **OK**.

## Update multiple inventory batches

1.  Click **Inventory management** \> **Periodic** \> **Batches** \> **Update shelf advice dates**.

2.  In the **Data calculation type** field, select the appropriate type to update this field.
    
      - **System** ─ The shelf advice date is calculated by using this formula: **Latest test date + Shelf advice period in days**.
    
      - **Fixed** ─ Select the new shelf advice date in the **Shelf advice date** field.

3.  In the **Shelf advice date** field, select the new shelf advice date.

4.  Click **Select** to enter selection criterion to locate the inventory batches you want to include in the batch job.

5.  Click **Batch** to enter the batch criterion to run a job that updates the shelf advice dates of the inventory batches you select.

6.  Click **OK** to run the batch job.

## See also

[Shelf advice (form)](https://technet.microsoft.com/library/hh227613\(v=ax.60\))

  


