---
title: (EEUR) Adjust the inventory value of a posted item
TOCTitle: (EEUR) Adjust the inventory value of a posted item
ms:assetid: 91ffca54-94e3-4cd6-8f3a-de4ff8b222c3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678297(v=AX.60)
ms:contentKeyID: 49387019
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Adjust the inventory value of a posted item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to adjust the financial value of the selected receipt transaction. The process recalculates the cost value of the item, and then adjusts the receipt transactions. The adjustments can be recorded as corrections in the general ledger.

### Prerequisite

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Ledger** area, on the **Accounting rules** FastTab, select the **Correction** check box to indicate that transactions that have negative amounts can be posted as corrections in the general ledger.

2.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**. In the **General** area, select the **Inventory adjustment - correction** check box to specify that inventory adjustments can be recorded as corrections in the general ledger.

### Adjust the inventory value of a posted form

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click **Adjustment** \>**Transactions**.

2.  In the **Adjust transactions** form, click **Select**, and then, in the **InventTransAdjustment** form, specify your selection criteria. When you are finished, click **OK**.
    
    For more information about how to select transactions in the **InventTransAdjustment** form, see [Inquiry (form)](https://technet.microsoft.com/en-us/library/aa575929\(v=ax.60\)).

3.  In the **Adjust transactions** form, click **Adjustment**, and then select an option.
    
    For information about the options in this menu, see [Adjust transactions (form) (Inventory)](https://technet.microsoft.com/en-us/library/aa585975\(v=ax.60\)).

4.  In the **Edit now** field, enter the revised value. Depending on the option that you selected in step 5, the value might be calculated for you, but you can change it.

5.  Click **Post**. In the **Adjust transactions** form, enter the required details.
    

    > [!TIP]
    > <P>The <STRONG>Inventory adjustment - correction</STRONG> check box is automatically selected. You can select or clear the check box manually.</P>



6.  Select the **Update ledger** check box to post the adjustment transactions in the general ledger.
    

    > [!IMPORTANT]
    > <P>If you do not select this check box, the cost price is adjusted in inventory transactions, but no adjustments are made in the general ledger.</P>



7.  Click **OK** to update the adjustment of the inventory transactions as corrections in the general ledger.

## See also

[(EEUR) Adjust the cost value of on-hand inventory](eeur-adjust-the-cost-value-of-on-hand-inventory.md)

[(EEUR) Inventory and warehouse management parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710787\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

