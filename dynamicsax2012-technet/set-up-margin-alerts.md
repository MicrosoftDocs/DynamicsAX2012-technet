---
title: Set up margin alerts
TOCTitle: Set up margin alerts
ms:assetid: cbf9d14b-8003-4589-9c5c-5ef45184af9c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497828(v=AX.60)
ms:contentKeyID: 62504015
ms.date: 06/11/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustParameters
- margin alert
- order entry
---

# Set up margin alerts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up margin alerts. A margin alert is triggered when you add an item to an order. The alert contains important information about the item, including the price margin and item profitability. You can use this information to decide whether a price override is appropriate when you add an item to the sales order.

You must complete the procedures in this topic before margin alerts can be applied to sales orders and purchase orders.

## Prerequisites

Before you can use margins and margin alerts, you must enable price details. For more information, see [Enable price details on orders](enable-price-details-on-orders.md).

## Set up margin alerts for sales orders

Use this procedure to set up margin alerts for sales orders. For example, you might set up thresholds for the trade margins to specify that a threshold of 40 percent or more above cost is acceptable for an item, and 20 to 39 percent above cost is questionable. This would mean that any item with a threshold between 20 and 39 percent will trigger a warning, and any item with a threshold below 20 percent above cost can’t be sold and the item price can’t be adjusted.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, in the left pane, click **Margin alerts**.

3.  Select the **Enable margin alert** check box.

4.  In the **Acceptable sales trade margin alert** field, enter the acceptable trade margin percentage. For example, if you enter 40 percent, the acceptable sales price is 40 percent or more above cost.

5.  In the **Questionable sales trade margin alert** field, enter the percentage at which the trade margin becomes questionable and requires review.
    
    The questionable sales trade margin value must be less than the acceptable sales trade margin.

## Set up margin alerts for purchase orders

Use this procedure to set up margin alerts for purchase orders.

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  In the **Procurement and sourcing parameters** form, in the left pane, click **Margin alerts**.

3.  Select the **Enable margin alert** check box.

4.  In the **Margin alert threshold** field, select the type of base price that you want to use for the margin alert. The margin alert threshold that you select will determine which estimated item sales price to select for the margin alerts calculation during the purchasing process.
    
    For example, item 4702 has a base sales price of 2,000.00. There are currently three trade agreements for this item with potential sales prices of 1,800.00, 1,500.00, and 1,100.00 for the customers.
    
      - **Optimistic Approach** – Select this option to apply the highest base price to the sale. In this example, the highest base price is 2,000.00 and any trade agreement sales prices are then applied.
    
      - **Pessimistic Approach** – Select this option to apply the lowest base price to the sale. In this example, the lowest base price is 1,100.00 and any trade agreement sales prices are then applied.
    
      - **Average Approach** – Select this option to apply the average of the base price and any trade agreement sales prices. In this example, the average base price is 1,600.00: (2000 + 1800 + 1500 + 1100) / 4 = 1,600.00.

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
<td><p><strong>Call center</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>System administrator</p></td>
</tr>
</tbody>
</table>


## See also

[Apply overrides](apply-overrides.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

