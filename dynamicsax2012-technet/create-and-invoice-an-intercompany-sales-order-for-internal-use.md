---
title: Create and invoice an intercompany sales order for internal use
TOCTitle: Create and invoice an intercompany sales order for internal use
ms:assetid: 4dbc79be-5d86-4fb9-862d-367b7f90b379
ms:mtpsurl: https://technet.microsoft.com/library/Aa497118(v=AX.60)
ms:contentKeyID: 43976713
author: Khairunj
ms.date: 04/11/2017
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create and invoice an intercompany sales order for internal use 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Typically, an intercompany sales order is created automatically, based on an intercompany purchase order. You can also manually create an intercompany sales order, which then generates an intercompany purchase order in the intercompany customer's legal entity.

![Intercompany example: Sale for internal use](images/Aa497118.IntercompanyInternalSalesProcess(AX.60).gif "Intercompany example: Sale for internal use")

## Create an intercompany sales order manually

Do these steps in legal entity B, as shown in the illustration.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **Action Pane**, click **Sales order** to create a sales order.

3.  In the **Create sales order** form, select a customer account. On the **General** FastTab, make sure that the **Intercompany** check box is selected. This indicates that the selected customer is an intercompany customer.

4.  Enter or modify the information, click **OK**, and then complete the order lines as usual.
    
    The **Delivery address** field value is copied from the intercompany sales order header to the intercompany purchase order header. The **Item number** field value, including product dimensions, and the **Delivery date** and **Currency code** field values are copied from the intercompany sales order lines to the intercompany purchase order lines.

5.  In the order header, click **Intercompany** to view the related intercompany purchase order.

6.  On the order lines, click **Intercompany** to view information about on-hand inventory for intercompany trade.
    

    > [!TIP]
    > <P>You can view intercompany sales orders in the <STRONG>Intercompany orders</STRONG> form.</P>




> [!NOTE]
> <P>When you work with intercompany, we recommend that you clear the <STRONG>Delete order after invoicing</STRONG> check box in the <STRONG>Accounts receivable parameters</STRONG> form. Otherwise, the related purchase order is deleted. We also recommend that you clear the <STRONG>Delete purchase order after invoicing</STRONG> check box in the <STRONG>Accounts payable parameters</STRONG> form.</P>



## See also

[Set up vendors, customers, and items for intercompany trade](set-up-vendors-customers-and-items-for-intercompany-trade.md)

[Create and invoice an intercompany sales order for an external customer](create-and-invoice-an-intercompany-sales-order-for-an-external-customer.md)

[Create and invoice an intercompany purchase order for internal use](create-and-invoice-an-intercompany-purchase-order-for-internal-use.md)

  


