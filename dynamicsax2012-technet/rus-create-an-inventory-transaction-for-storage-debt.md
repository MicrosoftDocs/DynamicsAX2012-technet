---
title: (RUS) Create an inventory transaction for storage debt
TOCTitle: (RUS) Create an inventory transaction for storage debt
ms:assetid: 47743a7a-ae81-4428-a0f4-9f531efa6960
ms:mtpsurl: https://technet.microsoft.com/library/JJ733214(v=AX.60)
ms:contentKeyID: 49685182
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create an inventory transaction for storage debt 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Forming of storage debt** form to create inventory transactions for storage debts for the services that are rendered to bailors.

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  In the **Inventory and warehouse management parameters** form, in the left pane, click **Journals**.

3.  In the **Journals** area, in the **Storage** field, select the name of an inventory movement journal.

4.  Close the form.

5.  Click **Accounts receivable** \> **Periodic** \> **Bailment** \> **Forming of storage debt**.

6.  Select the **Compress by days** check box to compress the storage transaction lines by days for payment of the storage service amount.

7.  In the **Customer account** field, select the account number for the owner of the items.

8.  In the **Sales agreement ID** field, select the sales agreement number for bailment.

9.  In the **Journal** field, select the inventory movement journal that is selected in the **Storage** field in the **Inventory and warehouse management parameters** form.

10. In the **Offset account** field, select the ledger account for inventory movement.

11. In the **Site**, **Warehouse**, **Inventory profile**, **Owner**, and **Batch number** fields, select the site, warehouse, inventory profile, owner, and batch number for bailment.

12. Click **OK** to create an inventory movement journal. The inventory movement journal is created for inventory movement transactions, based on the storage operations in the **Storage calculation operations** form. Journal lines are created for each calculation item, based on the grouping criteria that are selected in the **Grouping reference type** field in the **Transactions** form. The journal lines are posted based on the following conditions:
    
      - The **Inventory profile**, **Owner**, and **Batch number** check boxes must be selected for the item.
    
      - The batch number group must be specified for the calculation item.
    
      - A sales order must be created based on the on-hand inventory of the calculation item.

## See also

[(RUS) Forming of storage debt (form)](https://technet.microsoft.com/library/jj733205\(v=ax.60\))

  


