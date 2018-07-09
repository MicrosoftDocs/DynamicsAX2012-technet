---
title: (RUS) Create and post a purchase order based on an inventory profile
TOCTitle: (RUS) Create and post a purchase order based on an inventory profile
ms:assetid: 811201ea-f726-4080-bf1e-3c656233808b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733248(v=AX.60)
ms:contentKeyID: 49685215
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a purchase order based on an inventory profile [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Purchase order** form to post the packing slip, invoice, and facture for a purchase order. The inventory profile on the purchase order line must belong to the kind of activity that is selected in the purchase order, unless the kind of activity is **Unspecified**. The posting profile on the purchase order line is defined in the **Inventory profile - posting profile** form. Therefore, if the inventory profile is selected, the corresponding posting profile is selected automatically.

You can also post purchase indirect costs for purchase order lines that have an inventory profile with **Basic** as the kind of activity.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Create a purchase order, or select an existing purchase order. For more information, see [Create purchase order (form)](https://technet.microsoft.com/en-us/library/aa570189\(v=ax.60\)).

3.  Create a new purchase order line, or click **Add lines** to open the **Create lines** form.

4.  Click **Header view**, and then click the **Setup** FastTab.

5.  In the **Kind of activity** field, select **Basic**, **Commission agent**, **Principal's agent**, or **Bailee** as the profile type.

6.  In the **Inventory profile** field, select the required inventory profile.

7.  Click **Purchase** \> **Confirm** to confirm the purchase order.

8.  Click **Receive** \> **Product receipt** to post the packing slips for the purchase order.

9.  In the **Posting product receipt** form, on the **Overview** tab, in the **Product receipt** field, enter the product receipt number. On the **Lines** tab, modify the quantity that is ordered for each purchase order line in the packing slips, and then click **OK**.

10. In the **Purchase order** form, click **Invoice** \> **Facture** to post the invoice and update the facture for the purchase order.

11. In the **Update facture** form, on the **Vendor invoice** tab, in the **Number** and **Facture** fields, enter the invoice number and the facture number.
    

    > [!NOTE]
    > <P>The <STRONG>Kind of activity</STRONG> field on the <STRONG>Setup</STRONG> FastTab is updated based on the inventory profiles on the lines.</P>



12. Click **Retrieve product receipts** to select the packing slips in the **Select product receipt** form, and then click **OK**.

13. In the **Update facture** form, click **Facture** \> **Post** to select the posting settings and update the facture for selected packing slips. Both the invoice and facture are processed by using the specified document number and date.

14. The **Kind of activity** field is updated in the following locations:
    
      - On the **Overview** tab of the **Invoice journal** form (Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.)
    
      - On the **General** tab of the **Facture journal** form (Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Facture**.)

## See also

[(RUS) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj733294\(v=ax.60\))

[(RUS) Update factures and post invoices for open purchase orders](rus-update-factures-and-post-invoices-for-open-purchase-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

