---
title: Consume item requirements in a project
TOCTitle: Consume item requirements in a project
ms:assetid: 861743df-4f43-4913-b14a-e214f1f2ad99
ms:mtpsurl: https://technet.microsoft.com/library/Aa571578(v=AX.60)
ms:contentKeyID: 37822149
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- consume
- sales order
- item journal
- item requirements
audience: Application User
ms.search.region: Global
---

# Consume item requirements in a project 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, an item requirement is managed as a sales order line on a single sales order that is associated with a project. This item can be immediately consumed from inventory, or it can initiate a production order or purchase order for the item. Item consumption is recorded as a posting that registers that the item was used in the project.

If necessary, an item requirement can be partially consumed.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select or open a project for which you have created an item requirement.

3.  On the **Action Pane**, on the **Manage** tab, in the **New** group, click **Item task**, and then click **Item requirement**.
    
    –or–
    
    On the **Action Pane**, on the **Manage** tab, in the **Related information** group, click **Item tasks**, and then click **Item requirements**.

4.  Select the item requirement lines that are being consumed.

5.  On the menu bar, click **Posting**, and then click **Packing slip**.

6.  In the **Packing slip posting** form, on the **Parameters** tab, in the **Quantity** field, select the **All** option.

7.  Use the fields in the **Print options** group to specify how you want the packing slip to be printed.

8.  On the **Setup** tab, enter the date for the packing slip.

9.  Click **OK** to post the record, print the packing slip, and transmit the required information to the shipping carrier's software.

## See also

[About creating production orders for projects](about-creating-production-orders-for-projects.md)

[Create a sales order for a project](create-a-sales-order-for-a-project.md)

[Create customer invoices for sales orders](create-customer-invoices-for-sales-orders.md)

[Setting up and maintaining sales orders](setting-up-and-maintaining-sales-orders.md)

  


