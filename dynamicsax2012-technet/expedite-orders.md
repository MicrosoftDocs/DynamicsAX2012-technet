---
title: Expedite orders
TOCTitle: Expedite orders
ms:assetid: 4a8b566a-8dba-4d29-98d8-f35f2f26beb6
ms:mtpsurl: https://technet.microsoft.com/library/Dn497748(v=AX.60)
ms:contentKeyID: 62200064
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRExpediteTable
- MsDynAx060.Forms.MCRExpediteTable
- expedite
- expedite orders
- expedited orders
- expedited delivery
audience: Application User
ms.search.region: Global
---

# Expedite orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to expedite sales orders that are created in a call center. To use an expedited mode for an order, you must first set up codes that specify how much to expedite orders. You can optionally use one of these codes to set up a mode of delivery that is always expedited. Then, in the sales order, select either an expedite code or an expedited mode of delivery. These settings cause the order to be marked as expedited in the picking list.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<td><p>Required setup tasks</p></td>
<td><p><a href="set-up-a-call-center.md">Set up a call center</a></p></td>
</tr>
</tbody>
</table>


## 1\. Set up expedite codes

Set up codes that indicate how much to expedite the order. For example, you can set up a code that is named **High** to indicate that an order should be shipped as soon as possible, and a code that is named **Low** to indicate that the order has low shipping priority. You can use these codes in individual sales orders, or in the settings for one or more of the modes of delivery.

To set up expedite codes, follow these steps.

1.  Click **Sales and marketing** \> **Setup** \> **Distribution** \> **Expedite codes**.

2.  Click **New**, and then enter a code and a description.

3.  Close the form.

## 2\. Optional: Set up an expedited mode of delivery

You can specify that a particular mode of delivery is always expedited by using one of the expedite codes that you created in procedure 1.

To set up an expedited mode of delivery, follow these steps.

1.  Click **Sales and marketing** \> **Setup** \> **Distribution** \> **Modes of delivery**.

2.  Specify an expedited mode of delivery by following one of these steps:
    
      - Select one of the existing modes of delivery. In the **Expedite** field, select one of the expedite codes that you created in procedure 1. Close the form.
    
      - Click **New** to create a new mode of delivery. Enter the details for the mode of delivery, and then, in the **Expedite** field, select one of the expedite codes that you created in procedure 1. Close the form.

## 3\. Expedite an order

You can expedite a sales order by using an expedited mode of delivery or by applying an expedite code to the order.

To expedite an order, follow these steps.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  Create a new sales order, and enter information about the customer and the products that are being purchased.

3.  On the **Sales order header** FastTab, in the **Delivery details** section, in the **Mode of delivery** field, select a mode of delivery.
    
    By default, after you select a mode of delivery, the **Expedite** field is populated with the expedite code that was specified for that mode of delivery. If no code was specified for the mode of delivery, the **Expedite** field is empty.

4.  If the **Expedite** field isn't already set to the expedite code that you require, select the code.
    
    The code that you select in this field overrides the default code for the mode of delivery. The override affects the processing of the current sales order only.

5.  On the **Sales order lines** FastTab, add lines for the products to include in the order.

6.  By default, on the **Line details** FastTab, on the **Delivery** tab, the **Mode of delivery** and **Expedite** fields use the settings that you selected in the **Sales order header**. You can change these settings for each line, if changes are required.

7.  Continue to create the sales order by using the usual procedure. When you create the picking list for the expedited order, the message **\*\*Expedited\*\*** appears above the customer address.

## Next step

Set up picking and shipping processes to guarantee that the expedited order is shipped at an appropriate level of priority.

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
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager (to set up expedited delivery options)</p>
<p>Sales clerk (to create sales orders)</p></td>
</tr>
</tbody>
</table>


## See also

[Modes of delivery (form)](https://technet.microsoft.com/library/aa619881\(v=ax.60\))

  


