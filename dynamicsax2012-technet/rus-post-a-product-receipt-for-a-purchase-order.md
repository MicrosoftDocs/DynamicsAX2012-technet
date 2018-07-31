---
title: (RUS) Post a product receipt for a purchase order
TOCTitle: (RUS) Post a product receipt for a purchase order
ms:assetid: 34ec286f-f4b9-4597-884e-97fdd3602e24
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733198(v=AX.60)
ms:contentKeyID: 49685166
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- product receipt
- post a product receipt
audience: Application User
ms.search.region: Russia
---

# (RUS) Post a product receipt for a purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post a product receipt for a purchase order for items that you have specified the batch number, serial number, inventory owner, and customs cargo declaration number for.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order**, and then in the **Vendor account** field, select a vendor account.

3.  Click the **General** FastTab, and then in the **Purchase type** field, select **Purchase order**.

4.  Click **OK**.

5.  In the **Purchase order lines** grid, click **Add line** to create a purchase order line. At a minimum, you must specify an item, a procurement category, a purchase quantity, a unit, and a unit price.

6.  Click the **Line details** FastTab, and then click the **Product** tab.

7.  In the **Batch number**, **Serial number**, **Owner**, and **GTD number** fields, select the batch number, serial number, inventory owner, and customs cargo declaration number for the item.

8.  In the **Site**, **Warehouse**, and **Location** fields, select a site, warehouse, and location.

9.  On the **Action Pane**, click **Purchase** \> **Purchase order**.

10. Select the required print options, and then click **OK** to confirm the purchase order.

11. On the **Action Pane**, click **Receive** \> **Product receipt**.

12. In the **Receipt statement form type** field, select one of the following options to indicate whether the receipt statement is related to items or materials:
    
      - **Receipt statement for materials** – The receipt statement is related to materials.
    
      - **Receipt statement for items** – The receipt statement is related to items.

13. In the **Document about deviation** field, select one of the following options to indicate whether an M-7, TORG-1, TORG-2, or TORG-3 report is generated:
    
      - **Receipt statement for materials M-7** – The M-7 receipt statement for materials report is generated.
        

        > [!NOTE]
        > <P>This option is available only when you select <STRONG>Receipt statement for materials</STRONG> in the <STRONG>Receipt statement form type</STRONG> field.</P>

    
      - **Receipt statement for items TORG-1** – The TORG-1 receipt list for items report is generated.
    
      - **Receipt list for items TORG-2** – The TORG-2 receipt list for items report is generated.
    
      - **Receipt list for items TORG-3** – The TORG-3 receipt list for items report is generated.

14. In the lower pane, in the **Product receipt** field, enter the product receipt number.

15. Click **OK** to post the product receipt.

## See also

[(RUS) Correct a product receipt and print the receipt statement report](rus-correct-a-product-receipt-and-print-the-receipt-statement-report.md)

  


