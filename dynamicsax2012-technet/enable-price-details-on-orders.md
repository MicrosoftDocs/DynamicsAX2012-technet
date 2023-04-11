---
title: Enable price details on orders
TOCTitle: Enable price details on orders
ms:assetid: 886db97e-d55e-480d-9140-eada9a1858cc
ms:mtpsurl: https://technet.microsoft.com/library/Dn497797(v=AX.60)
ms:contentKeyID: 62110072
author: tonyafehr
ms.date: 04/14/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRPriceHistory
- price details
audience: Application User
ms.search.region: Global
---

# Enable price details on orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to enable and view price details in sales orders and purchase orders. After price details are enabled, workers can look up pricing information for order lines. Information that workers can view includes unit prices, discount amounts, margin estimations, trade agreements, and rebate amounts.

## Enable price details

Use these procedures to enable the **Price details** form for sales orders and purchase orders.

To enable price details for purchase orders, follow these steps.

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  In the left pane, click **Prices**.

3.  Under **Price details**, select the **Enable price details** check box.

To enable price details for sales orders, follow these steps.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the left pane, click **Prices**.

3.  Under **Price details**, select the **Enable price details** check box.


> [!NOTE]
> <P>If you want to view margin estimations in the <STRONG>Price details</STRONG> form, you must set up and enable margin alerts as described in Set up margin alerts.</P>
> <P>Many of the other pricing options that are displayed in the <STRONG>Price details</STRONG> form require setup. For example, if you want to view vendor rebates, you must first set up vendor rebate agreements as described in <A href="set-up-vendor-rebate-agreements.md">Set up vendor rebate agreements</A>.</P>



## View price details

After price details have been enabled, you can view price information for order lines at the time of order entry or any time after.

To view price details, follow these steps.

1.  Create a purchase order or a sales order, and add a line to the order.

2.  For a purchase order, on the **Purchase order lines** FastTab, click **Purchase order line**, and then, under **View**, click **Price details**.
    
    –or–
    
    For a sales order, on the **Sales order lines** FastTab, click **Sales order line**, and then, under **View**, click **Price details**.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Trade agreements</strong> configuration key</p>
<p><strong>Margin alert</strong> configuration key (if you use margin alerts)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager (to enable price details)</p>
<p>Sales clerk (to create sales orders and view price details)</p>
<p>Purchasing agent (to create purchase orders and view price details)</p></td>
</tr>
</tbody>
</table>

  


