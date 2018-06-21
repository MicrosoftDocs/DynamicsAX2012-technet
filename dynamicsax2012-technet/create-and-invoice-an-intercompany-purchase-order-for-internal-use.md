---
title: Create and invoice an intercompany purchase order for internal use
TOCTitle: Create and invoice an intercompany purchase order for internal use
ms:assetid: 88539143-5c09-4e4b-80ea-48fb87137164
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498226(v=AX.60)
ms:contentKeyID: 43976719
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create and invoice an intercompany purchase order for internal use [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create an intercompany purchase order for an intercompany vendor. This automatically creates an intercompany sales order at the intercompany vendor.

![Intercompany process: Purchase for internal use](images/Aa498226.IntercompanyPurchaseProcess(AX.60).gif "Intercompany process: Purchase for internal use")

## Create an intercompany purchase order and a corresponding intercompany sales order

Do these steps in legal entity AAA, as shown in the illustration.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **All purchase orders** list page, create a purchase order for an intercompany vendor. The field values are copied from the vendor account to the purchase order.
    
    Because you are working with an intercompany vendor, an intercompany sales order is created in the legal entity that corresponds to the vendor. The number of the intercompany sales order can be the same as the number of the intercompany purchase order, and it can include the ID of the legal entity. The number structure that is used depends on the selection in the **Sales order numbering** field in the **Intercompany** form. For example, if you create purchase order 00029\_064 in legal entity AAA, the sales order number in legal entity BBB is AAA00029\_64.
    
    An Infolog message tells you that an intercompany purchase order and intercompany sales order have been created. The message includes the intercompany sales order number, for your information.

3.  Add line items to the purchase order. The corresponding line items are added automatically to the intercompany sales order. If an item does not exist in the other legal entity, a message is displayed and you cannot add the item to the purchase order. To fix this problem, switch to the other legal entity and release the product to that legal entity. The item will be available to be added to sales orders in that legal entity. Then, switch back to the legal entity of the purchase order and continue adding line items.

4.  When you have finished entering information for the purchase order, confirm it.

## Process the intercompany packing slip and customer invoice

Do these steps in legal entity BBB, as shown in the illustration.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **All sales orders** list page, select the intercompany sales order.

3.  On the **Action Pane**, click the **Pick and pack** tab, and then click **Packing slip**.

4.  Select the **Posting** check box.

5.  Click **OK**. The packing slip is posted in legal entity BBB.

6.  On the **All sales orders** list page, select the intercompany sales order.

7.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**.

8.  Select the **Posting** check box.

9.  Click **OK**.
    
    The customer invoice for the intercompany sales order is posted in legal entity BBB.

## Process the intercompany product receipt and vendor invoice

Do these steps in legal entity AAA, as shown in the illustration.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **All purchase orders** list page, select the intercompany purchase order.

3.  On the **Action Pane**, click **Receive**, and then click **Product receipt**. The product receipt is created. The product receipt number is the same as the intercompany packing slip number.

4.  Select the **Posting** check box.

5.  Click **OK**.

6.  On the **All purchase orders** list page, select the intercompany purchase order.

7.  On the **Action Pane**, click **Invoice**, and then click **Invoice**. The vendor invoice is created. The vendor invoice number is the same as the intercompany customer invoice number.

8.  Finish entering the vendor invoice, and then post it.

## See also

[Set up vendors, customers, and items for intercompany trade](set-up-vendors-customers-and-items-for-intercompany-trade.md)

[Create and invoice an intercompany sales order for internal use](create-and-invoice-an-intercompany-sales-order-for-internal-use.md)

[Create and invoice an intercompany sales order for an external customer](create-and-invoice-an-intercompany-sales-order-for-an-external-customer.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

