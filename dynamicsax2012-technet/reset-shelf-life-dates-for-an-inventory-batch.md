---
title: Reset shelf life dates for an inventory batch
TOCTitle: Reset shelf life dates for an inventory batch
ms:assetid: ba1f65ac-8124-4686-a12f-d4a517b41ac8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352341(v=AX.60)
ms:contentKeyID: 36687971
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reset shelf life dates
- shelf life date for inventory batch
- shelf life for inventory batch
---

# Reset shelf life dates for an inventory batch [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to reset the shelf life date for an inventory batch. The shelf life defines the effective period of a product as measured in days, months, or years. Reports and picking strategies for products are determined based on the shelf life of a particular lot by using FIFO (First In, First Out) rules.

1.  Click **Inventory management** \> **Inquiries** \> **Dimensions** \> **Batches**.

2.  Select the inventory batch to update.

3.  Click **Reset shelf life dates**.

4.  In the **Reset shelf life dates** form, select a new date in the date field that you want to change.
    
      - **Manufacturing date** ─ Select the date when the batch was produced in a batch order or received in a purchase order. You can also use the vendor’s manufacturing date if this information is provided when vendor batch details are updated. The manufacturing date must be before the best before and expiration dates. If you change the manufacturing date, you are asked whether to recalculate the shelf advice, best before date, and expiration date. Click **Yes** to accept, or else click **No**.
    
      - **Shelf advice date** ─ Select the recommended date when a batch or lot should be retested to validate that it still meets testing standards.
    
      -  **Best before date** ─ Select the date before an inventory batch is best used. If you change the best before date, you are asked whether to recalculate the expiration date. Click **Yes** to accept, or else click **No**.
    
      - **Expiration date** ─ Select the date when the inventory batch expires. If you change the expiration date, you are asked whether to recalculate the best before date. Click **Yes** to accept, or else click **No**.

5.  Click **OK**.

## See also

[Shelf life as of date (form)](https://technet.microsoft.com/en-us/library/hh227671\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

