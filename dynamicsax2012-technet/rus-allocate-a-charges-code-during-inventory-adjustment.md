---
title: (RUS) Allocate a charges code during inventory adjustment
TOCTitle: (RUS) Allocate a charges code during inventory adjustment
ms:assetid: 2c0aa624-43fd-4336-bd3a-e7ff8be05f53
ms:mtpsurl: https://technet.microsoft.com/library/JJ923269(v=AX.60)
ms:contentKeyID: 52075361
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Allocate a charges code during inventory adjustment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedures to allocate a charge code during inventory adjustment. You can allocate charge codes during inventory adjustment from the **On-hand**, **Adjust transactions** and, **Wizard for cost value adjustment of inventory transactions or entire on-hand inventory** forms.

## Allocate a charge code during inventory adjustment in the Adjustment of on-hand inventory form

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click **Adjustment** \> **On-hand** to open the **On-hand** form. For more information, see [(RUS) Adjustment of on-hand inventory (modified form)](https://technet.microsoft.com/library/jj923554\(v=ax.60\)).

2.  In the **Charges code** field, select a charge code.
    

    > [!NOTE]
    > <P>You must select a charge code with a debit type of <STRONG>Item</STRONG> and a credit type of <STRONG>Ledger account</STRONG>. You can also modify the miscellaneous charge code and update it for all transaction lines by clicking <STRONG>Adjustment</STRONG> &gt; <STRONG>Charges code</STRONG>.</P>



3.  Click **Post** to update the settlement of inventory transactions.

## Allocate a charge code for inventory adjustment in the Adjust transactions form

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click **Adjustment** \> **Transactions** to open the **Adjust transactions** form.

2.  Click **Select** to select a line to adjust.

3.  In the **Charges code** field, select a charge code.
    

    > [!NOTE]
    > <P>You must select a charge code with a debit type of <STRONG>Item</STRONG> and a credit type of <STRONG>Ledger account</STRONG>. You can also modify the miscellaneous charge code and update it for all transaction lines by clicking <STRONG>Adjustment</STRONG> &gt; <STRONG>Charges code</STRONG>.</P>



4.  Click **Post**, and then click **OK** to update the settlements.

## Allocate a charge code for inventory adjustment by using the cost adjustment wizard

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click **Adjustment** \> **Wizard** to open the **Wizard for cost value adjustment of inventory transactions or entire on-hand inventory** form.
    
    You can allocate a charge code for inventory adjustment by using the cost adjustment wizard. For more information, see [(RUS) Wizard for cost value adjustment of inventory transactions or entire on-hand inventory (form)](https://technet.microsoft.com/library/jj733512\(v=ax.60\)).

2.  Run the wizard to complete the adjustment process.

## Close an adjusted inventory

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**.

2.  Click **Close procedure** \> **3. Close** to open the **Close inventory** form.

3.  Click **OK** to close the inventory. For more information, see [Run inventory close](run-inventory-close.md).


> [!NOTE]
> <P>Use the <STRONG>Cost explorer</STRONG> form to view the cost structure of an inventory item. (Click <STRONG>Inventory management</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>On-hand inventory</STRONG>. Select the item, and then double-click to open the <STRONG>On-hand</STRONG> – <STRONG>Item number</STRONG> form. Click <STRONG>Transactions</STRONG>, and then click <STRONG>Inventory</STRONG> &gt; <STRONG>Cost explorer</STRONG>.) After closing the inventory, you can view both the receipt and issue inventory transactions. The inventory settlements are split by miscellaneous charge codes and displayed in this form. You can also view the inventory cost in the reporting currency.</P>



## Close and adjust inventory in the reporting currency

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. To open an existing purchase order, double-click the purchase order. To create a purchase order, on the **Action Pane**, on the **Purchase order** tab, click **Purchase order**.

2.  In the **Purchase order** form, select an item, and then enter purchase order line details to allocate the charges. For more information, see [(RUS) Create and post a vendor invoice to allocate charges](rus-create-and-post-a-vendor-invoice-to-allocate-charges.md).

3.  On the **Purchase** tab, click **Allocate charges** to allocate the charges for the selected lines on a purchase order invoice. For more information, see [Allocate charges (form)](https://technet.microsoft.com/library/hh697725\(v=ax.60\)) and [Adjust charges on vendor invoices](adjust-charges-on-vendor-invoices.md).

4.  Click **Confirm**, and then, on the **Invoice** tab, click **Invoice** to post the vendor invoice.

5.  Click **Inventory management** \> **Periodic** \> **Close and adjustment in currency**.

6.  Select a record, and then click **Adjustment** \> **Wizard**.

7.  On the **Method of cost value adjustment** page, click **Transactions**. In the **Inquiry** form, select the item number that is allocated to the charges in the **Purchase order** form, and then click **OK**. You can view the items or item transactions that are selected for adjustment. Click **Next**.

8.  On the **Results of allocation** page, in the **Charges code** field, select the charge code.

9.  In the **Amount for allocation** field, enter the charge amount to adjust when posting. For more information, see [(RUS) Wizard for cost value adjustment of inventory transactions or entire on-hand inventory (form)](https://technet.microsoft.com/library/jj733512\(v=ax.60\)).

10. Click **Next** to complete the closing and adjustment in the reporting currency. You can allocate the charges by using the **Adjust transactions in currency** form. In this form, select the line for correction, and then click **Adjustment** \> **Charges code** to allocate the charges. For more information, see [(RUS) Adjust transactions (modified form)](https://technet.microsoft.com/library/jj923588\(v=ax.60\)).
    

    > [!NOTE]
    > <P>You can also allocate the charges by using the <STRONG>On-hand</STRONG> form. In this form, select the line for correction, and then click <STRONG>Adjustment</STRONG> &gt; <STRONG>Charges code</STRONG> to allocate the charges. For more information, see <A href="https://technet.microsoft.com/library/jj923554(v=ax.60)">(RUS) Adjustment of on-hand inventory (modified form)</A>.</P>



11. In the **Closing and adjustment** form, click **Close procedure** \> **3. Close** to close the inventory in the reporting currency for the specified period. For more information, see [Run inventory close](run-inventory-close.md).

12. In the **Purchase order** form, on the **Purchase order lines** FastTab, click **Inventory** \> **Transactions** to open the **Inventory transactions** form. To view the inventory cost structure in the reporting currency for the posted purchase order, click **Cost explorer**, and then, in the **Currency** field, select **Reporting currency**.

## See also

[(RUS) Create a purchase order and assign charges to the purchase invoice](rus-create-a-purchase-order-and-assign-charges-to-the-purchase-invoice.md)

[(RUS) Adjust a cost price using the adjustment wizard](rus-adjust-a-cost-price-using-the-adjustment-wizard.md)

  


