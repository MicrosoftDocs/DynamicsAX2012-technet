---
title: Update best before dates for inventory batches
TOCTitle: Update best before dates for inventory batches
ms:assetid: e77a9b79-2c5e-4c56-ab65-a5684ccc2e13
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh328598(v=AX.60)
ms:contentKeyID: 36688024
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- change the best before date
- change the use before date
- update the best before date
- update use before date
---

# Update best before dates for inventory batches [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to update the best before date that is applied to a single inventory batch or multiple inventory batches. This date defines the date when an inventory batch should be used.

## Update a single inventory batch

1.  Click **Inventory management** \> **Inquiries** \> **Batches** \> **Best before as of date**.

2.  Click **Functions** and select **Reset shelf life dates**. The **Reset shelf life dates** dialog box is displayed.

3.  In the **Best before date** field, select the new date.

4.  Click **OK**.

## Update multiple inventory batches

1.  Click **Inventory management** \> **Periodic** \> **Batches** \> **Update best before dates**.

2.  In the **Data calculation type** field, select the appropriate type to update this field.
    
      - **System** ─ Calculates the best before date by using this formula: **Best before date = Expiration date ─ Best before period in days**.
    
      - **Fixed** ─ Select the new best before date in the **Best before date** field.

3.  Click **Select** to enter criterion to filter the inventory batches that you want to include in the batch job.

4.  On the **Batch** tab, enter the batch criterion to run a job that updates the best before dates of the inventory batches you select.

5.  Click **OK** to run the batch job.

## See also

[Best before as of date (form)](https://technet.microsoft.com/en-us/library/hh227546\(v=ax.60\))

[Update best before dates (form)](https://technet.microsoft.com/en-us/library/hh209458\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

