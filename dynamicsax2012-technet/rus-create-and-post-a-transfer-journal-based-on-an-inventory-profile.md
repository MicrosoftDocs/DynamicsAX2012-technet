---
title: (RUS) Create and post a transfer journal based on an inventory profile
TOCTitle: (RUS) Create and post a transfer journal based on an inventory profile
ms:assetid: 8eac47c0-9f57-4155-bdfe-316758697e75
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678471(v=AX.60)
ms:contentKeyID: 49387700
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a transfer journal based on an inventory profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Transfer** form to create and post a transfer journal based on the inventory profile. The transfer journal line can have different values for the inventory profiles, but the values should belong to the same kind of activity. When you post a journal, there can be transactions in the general ledger if inventory profiles have different accounts in inventory posting.

1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Transfer**.

2.  Create an inventory journal.

3.  Click **Lines** to open the **Journal lines, inventory** form.

4.  Create a journal line.

5.  On the **Overview** tab, in the **Date** field, select the transaction date.

6.  In the **Item number** field, select the item number of the inventory to post.

7.  In the **From configuration** field, select the configuration of the item that is being moved from the source warehouse.

8.  In the **To configuration** field, select the configuration of the item that is being moved to the destination warehouse.

9.  On the **Inventory dimensions** tab, in the **From inventory dimensions** field group, in the **Site** field, select the site from which the inventory is moved.

10. In the **To inventory dimensions** field group, in the **Site** field, select the site to which the inventory is moved.

11. In the **Inventory profile** field, select the inventory profile.

12. Click **Post** to post the journal.

## See also

[Journal lines, Inventory movement (form)](https://technet.microsoft.com/en-us/library/aa598740\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

