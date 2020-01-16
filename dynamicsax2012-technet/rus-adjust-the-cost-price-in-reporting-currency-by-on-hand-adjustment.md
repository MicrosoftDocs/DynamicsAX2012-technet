---
title: (RUS) Adjust the cost price in reporting currency by on-hand adjustment
TOCTitle: (RUS) Adjust the cost price in reporting currency by on-hand adjustment
ms:assetid: 23033383-4874-4373-a045-cfa979b770fe
ms:mtpsurl: https://technet.microsoft.com/library/JJ733187(v=AX.60)
ms:contentKeyID: 49685155
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- adjustment
- cost price
- (RUS)
- Russia
audience: Application User
ms.search.region: Russia
---

# (RUS) Adjust the cost price in reporting currency by on-hand adjustment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you run the inventory closing process, you can adjust the inventory cost price for the remaining inventory items. The adjustment amount is assigned to all open receipts. You can perform adjustments of on-hand inventory only after the inventory closing process is run. You can view the adjusted amounts in the **Adjustment (cur.)** field in the **Transactions** form. For more information, see [(RUS) Inventory transactions (modified form)](https://technet.microsoft.com/library/jj733410\(v=ax.60\)).

1.  Click **Inventory management** \> **Periodic** \> **Close and adjustment in currency**.

2.  Select a line that has a transaction type of **Closing accounts**, and then click **Adjustment** \> **On-hand**.

3.  Click **Select**, and then select the inventory dimensions to copy to adjust on-hand inventory. For more information, see [Select on-hand inventory (class form)](https://technet.microsoft.com/library/aa585980\(v=ax.60\)).

4.  Click **OK**. The inventory lines that are selected for adjustment are displayed in the **On-hand** form, together with the specified inventory dimensions.
    

    > [!NOTE]
    > <P>To redefine the inventory dimensions that you copy, click <STRONG>Delete</STRONG> to remove the existing lines, and then click <STRONG>Select</STRONG> to specify the inventory dimensions.</P>



5.  In the **Edit now** field, enter the amount that is used to adjust on-hand inventory.

6.  Click **Adjustment**, and then select the method that is used to adjust on-hand inventory, from the following options:
    
      - **Charges code** – Specify a charges code for all the adjustments that are selected. The adjustments are posted based on the setup of the charges code. The charges code is saved in the settlement records that are created for the adjustment.
    
      - **Item cost price** − After adjustment, the item cost price is equal to the standard price that is specified in the **Price** field on the **Manage costs** FastTab in the **Released product details** form.
    
      - **Fixed cost price** − Open the **Adjustment to fixed cost price** form, and then in the **Price** field, enter the fixed cost price for the inventory item. After adjustment, the item cost price is adjusted to so that it matches the unit price.
        

        > [!NOTE]
        > <P>The value of the adjustment is displayed in the <STRONG>Edit now</STRONG> field in the <STRONG>On-hand</STRONG> form, based on the selected adjustment method. The adjustment value is the difference between the current cost value and the target cost value. You can modify the adjustment value in the <STRONG>Edit now</STRONG> field.</P>

    
      - **Amount** − Open the **Adjustment with amount** form. In the **Amount** field, enter the increase or decrease in the inventory cost value according to the allocation principle that is selected in the **Allocation principle** field. After adjustment, the total cost value is increased or decreased by the specified amount, in proportion to the quantity or cost price of the on-hand inventory.
    
      - **Value** − Open the **Adjustment to value** form, and then in the **Value** field, enter the total inventory value after adjustment.
    
      - **Percent** − Open the **Percentage adjustment** form. In the **Percent** field, enter the percentage value that is used to adjust the total cost value for the selected item.

7.  Click **Post**, and then in the **Specification** field, select how transaction adjustments are posted, from the following options:
    
      - **Total** – Adjustments are posted for all items that have the same settings in the posting profile.
    
      - **Item group** – Adjustments are posted for all items that have the same item group.
    
      - **Item number** – Adjustments are posted for each item.

8.  In the **Note** field, enter a note about the adjustment.

9.  Click **OK** to post the adjustment results.

## See also

[(RUS) Adjust cost price by inventory receipt adjustment](rus-adjust-cost-price-by-inventory-receipt-adjustment.md)

[(RUS) Adjust the cost price from the ledger account](rus-adjust-the-cost-price-from-the-ledger-account.md)

  


