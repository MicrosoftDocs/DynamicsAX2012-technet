---
title: (IND) Create a purchase order and post charges
TOCTitle: (IND) Create a purchase order and post charges
ms:assetid: 7d47c31d-5f53-4c18-86c9-b7288f16936a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677944(v=AX.60)
ms:contentKeyID: 49385907
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Create a purchase order and post charges 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

According to legal regulations, taxes and charges must be calculated on all business transactions. You can enter or modify charges on an invoice that has not been posted to match the paper copy that is received from the vendor. You can add, modify, or delete charge transactions on the invoice header and allocate the transactions to invoice lines or to the header level. You can also add, modify, or delete invoice charge transaction lines.

## Create a purchase order

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. To create a new purchase order, on the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.


> [!NOTE]
> <P>For more information, see "<A href="create-a-purchase-order.md">Create a purchase order</A>" in the Applications and Business Processes Help.</P>



## View or modify charges

1.  In the **Purchase order** form, on the **Action pane**, on the **Purchase** FastTab, in the **Charges** group, click **Manage charges**.

2.  View or modify the charges code to calculate charges for the transaction in the **Charges code** field.
    

    > [!NOTE]
    > <P>You can also create a new charges transaction line.</P>



3.  View or modify the charges category for the purchase order in the **Category** field.

4.  View or modify the value of the charges for the charges category in the **Charges value** field.

5.  In the **Purchase order** form, on the **Action pane**, on the **Purchase** FastTab, in the **Charges** group, click **Allocate charges**.

6.  Select the method for allocating charges in the **Charges allocation** field. Select the **Whole amount** option to allocate the total charge amount to each order line entered in the **Charges transactions** form.
    
      - If you select **Percent** in the **Category** field in the **Charges transactions** form, the **Whole amount** is not available in the **Charges allocation** field.
    
      - If there is more than one charge code and one of them has the category set to **Percent**, the **Whole amount** is not available in the **Charges allocation** form.

7.  Enter the other required details.

8.  Click **Allocate** to allocate the charges.

9.  Click the **Purchase** FastTab, in the **Charges** group, click **Manage charges** to view or modify the charges in the **Charges transactions** form.
    

    > [!NOTE]
    > <P>You can create a new charges transaction line.</P>



10. View or modify the charge code to calculate miscellaneous charges for the transaction in the **Charges code** field.

11. View or modify the charges category and the miscellaneous charges for the purchase order. You can view the allocation method that is used for the charges code in the **Charges allocation** field after the allocation.

12. Close the **Charges transactions** form.

## Post the invoice with charges

1.  On the **Action pane**, on the **Invoice** FastTab. In the **Generate** group, click **Invoice** to create the invoice.

2.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

3.  Select the vendor invoice. On the **Action pane**, click **Charges** to view the charges that are posted for the transaction.

## Calculate charges for an intercompany transaction

You can also set up and calculate charges for an intercompany transaction.

You must set up a charge code with the category set to **Intercompany percent**. When you create an intercompany purchase order or sales order, the charges code defined for the customer or vendor and item combination is used to calculate charges.

A sales order or purchase order is created automatically for the intercompany for the original purchase order or sales order when the charges category is set to **Intercompany percent**. The charges are added to both the original order and the automatically created order to match the invoice amounts.

## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

