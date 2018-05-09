---
title: Set up intercompany trade
TOCTitle: Set up intercompany trade
ms:assetid: a8629f81-c528-4140-b615-05542da2bb64
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550312(v=AX.60)
ms:contentKeyID: 43976723
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- intercompany trade
---

# Set up intercompany trade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To enable Microsoft Dynamics AX to run intercompany trade, you must set up customers and vendors to run intercompany trade. You must also set up Accounts payable, Accounts receivable, Procurement and sourcing, and Sales and marketing.

## Before you set up intercompany trade

Before you set up intercompany trade, you must decide which customers are intercompany customers, and which vendors are intercompany vendors. For each legal entity in Microsoft Dynamics AX, you must decide which trading policy to apply to the intercompany trading relation with the specific intercompany customer or vendor.

In particular, we recommend that you and your organization become familiar with the intercompany parameters. For more information, see [Intercompany setup (form)](https://technet.microsoft.com/en-us/library/hh781085\(v=ax.60\)).

  - Discuss the implications of the setup with the managers who are responsible for intercompany trade in each legal entity.

  - Set up the appropriate values for each legal entity.

## Set up trading relations

To set up intercompany trade for customers and vendors, follow these steps.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account.

3.  On the **Action Pane**, on the **General** tab, click **Intercompany**.

4.  Specify intercompany setup parameters for the customer account. These parameters include the legal entity that contains the corresponding vendor and the vendor account. The parameters also include the purchase order policies, sales order policies, value mapping, and policies for sales agreements and purchase agreements. You also specify whether to use base data values from the customer account or from the vendor account in the other legal entity.

5.  Repeat steps 1 through 4 for the remaining intercompany customers in the legal entity.

6.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

7.  Select a vendor account.

8.  On the **Action Pane**, on the **General** tab, click **Intercompany**.

9.  Specify intercompany setup parameters for the vendor account. These parameters include the legal entity that contains the corresponding customer and the customer account. The parameters also include the sales order policies, purchase order policies, value mapping, and policies for purchase agreements and sales agreements. You also specify whether to use base data values from the vendor account or from the customer account in the other legal entity.

10. Repeat steps 6 through 9 for the remaining intercompany vendors in the legal entity.

## Set up products

To set up intercompany trade for customers and vendors, follow these steps.

1.  Click **Product information management** \> **Common** \> **Products** \> **All products and product masters**.

2.  Define the products that are released to the legal entities where you want to do intercompany trade. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

## See also

[Create and invoice an intercompany purchase order for internal use](create-and-invoice-an-intercompany-purchase-order-for-internal-use.md)

[Create and invoice an intercompany sales order for internal use](create-and-invoice-an-intercompany-sales-order-for-internal-use.md)

[Create and invoice an intercompany sales order for an external customer](create-and-invoice-an-intercompany-sales-order-for-an-external-customer.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

