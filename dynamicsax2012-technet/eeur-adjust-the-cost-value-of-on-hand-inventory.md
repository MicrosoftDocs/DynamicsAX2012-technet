---
title: (EEUR) Adjust the cost value of on-hand inventory
TOCTitle: (EEUR) Adjust the cost value of on-hand inventory
ms:assetid: e81d59f7-f042-49aa-845b-b611b7a920db
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711302(v=AX.60)
ms:contentKeyID: 49387120
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Adjust the cost value of on-hand inventory 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to adjust the cost value of complete on-hand inventories. The process recalculates the cost value of on-hand inventory quantities after an inventory close process is run, and then adjusts the transactions. The adjustments can be recorded as corrections in the general ledger.

### Prerequisite

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Ledger** area, on the **Accounting rules** FastTab, in the **Transaction reversal** field group, select the **Correction** check box so that transactions that have negative amounts can be posted as corrections in the general ledger.

2.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**. In the **General** area, in the **Correction** field group, select the **Inventory adjustment - correction** check box to specify that adjustments to on-hand inventory can be recorded as corrections in the general ledger.

### Adjust the cost value of on-hand inventory

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click **Adjustment** \> **On-hand**.
    

    > [!NOTE]
    > <P>You must run at least one closing before an item can be adjusted as on-hand inventory.</P>



2.  In the **On-hand** form, click **Select**.

3.  In the **Select on-hand inventory** form, select which inventory dimensions you want to copy to the on-hand adjustment journal for subsequent adjustment. Click **Select** to refine the selection criteria. For example, you can use a query to select a specific item. For more information about using queries to select records, see [Inquiry (form)](https://technet.microsoft.com/en-us/library/aa575929\(v=ax.60\)).

4.  After you select the on-hand inventories to adjust, click **OK** to close the **Select on-hand inventory** form.

5.  In the **On-hand** form, click **Post**, and then in the **Adjustment of on-hand inventory** form, enter the required details.
    

    > [!TIP]
    > <P>The <STRONG>Inventory adjustment - correction</STRONG> check box is automatically selected. You can select or clear the check box manually if you need to.</P>



6.  Click **OK** to post the journal and update adjustments of the on-hand inventory as corrections in the general ledger.

## See also

[Closing and adjustment (form)](https://technet.microsoft.com/en-us/library/aa553192\(v=ax.60\))

[Select on-hand inventory (class form)](https://technet.microsoft.com/en-us/library/aa585980\(v=ax.60\))

[Adjustment of on-hand inventory (form)](https://technet.microsoft.com/en-us/library/aa553861\(v=ax.60\))

[(EEUR) Adjust the inventory value of a posted item](eeur-adjust-the-inventory-value-of-a-posted-item.md)

[(EEUR) Inventory and warehouse management parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710787\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

