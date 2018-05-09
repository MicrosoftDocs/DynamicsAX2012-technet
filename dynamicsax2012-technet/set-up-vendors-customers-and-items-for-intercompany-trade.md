---
title: Set up vendors, customers, and items for intercompany trade
TOCTitle: Set up vendors, customers, and items for intercompany trade
ms:assetid: 0c6ea241-c899-4ea7-aae8-221a58d6bbfd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569754(v=AX.60)
ms:contentKeyID: 43976702
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up vendors, customers, and items for intercompany trade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To prepare your organization for intercompany trade, you must define the vendors and customers with whom you will be trading internally. You must then associate these vendors and customers with the items that you will be purchasing or selling.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select the vendor to define as an intercompany vendor.

3.  On the **Action Pane**, on the **General** tab, click **Intercompany**.

4.  Specify intercompany setup parameters for the vendor account. These parameters include the customer legal entity and account, sales order policies, purchase order policies, value mapping, and purchase agreement and sales agreement policies. You also specify whether to use base data values from the vendor account or from the customer account in the other legal entity.

5.  Click **Product information management** \> **Common** \> **Released products**.

6.  On the **Released products** list page, select the items to assign to the vendor, so that the items are available for intercompany trade. For each item, double-click the line to open the **Released product details** form. On the **Purchase** tab, in the **Vendor** field, type the vendor number.

7.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

8.  Select the customer to define as an intercompany customer.

9.  On the **Action Pane**, on the **General** tab, click **Intercompany**.

10. Specify intercompany setup parameters for the customer account. These parameters include the vendor legal entity and account, purchase order policies, sales order policies, value mapping, and sales agreement and purchase agreement policies. You also specify whether to use base data values from the customer account or from the vendor account in the other legal entity.

11. In the **Customers** form, on the **Invoice and delivery** FastTab, select the **Create intercompany orders** check box. If you want orders to be delivered directly to customers, select the **Direct delivery** check box.
    

    > [!NOTE]
    > <P>If there are some items that your organization stocks and delivers to customers, you might not want to create intercompany orders automatically, even when you have the item in stock. To inactivate the automatic generation of orders for items that you might sometimes have in stock, clear the <STRONG>Create intercompany orders</STRONG> check box.</P>



12. If you want to allow extra lines to be created indirectly on a sales order, select the **Create indirect order lines** check box. A user can then add lines to the original sales order from the intercompany sales order.


> [!WARNING]
> <P>If you allow order lines to be created indirectly, you are permitting all additions to the original sales order from the intercompany sales order. Each addition is then processed through to the customer, and is added to the order and the invoice. Additionally, every document that is involved in the sale is printed and posted automatically. Users are not alerted about the addition.</P>



## See also

[Set up intercompany trade](set-up-intercompany-trade.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

