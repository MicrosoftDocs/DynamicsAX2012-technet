---
title: Delete outdated sales orders for a call center
TOCTitle: Delete outdated sales orders for a call center
ms:assetid: 143a1ef1-ff3f-4b36-b80f-29d07f21f7f3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720456(v=AX.60)
ms:contentKeyID: 62224163
ms.date: 04/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Delete outdated sales orders for a call center 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

At some point, your organization will need to remove outdated order information from Microsoft Dynamics AX. This topic explains how to delete invoiced and canceled sales orders that were generated in the call center.

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


## Delete sales orders in the call center

The following procedure explains how to delete sales orders that were generated in the call center.

1.  Click **Call center** \> **Periodic** \> **Clean up** \> **Sales order purge**.

2.  In the **Sales order purge** form, do one of the following:
    
      - In the **Customer account** field, select the customer account for which you are deleting sales orders. In the **Invoice aged days** field, enter the number of days up to today’s date for which invoiced and canceled sales orders that were created for the selected customer should be deleted. For example, if today is April 1, 2014, and you enter 30, all invoiced or canceled sales orders created on or before March 2, 2014 will be deleted.
    
      - In the **Customer account** field, select the customer account for which you are deleting sales orders. In the **Last invoiced through** field, select the date on which all invoiced or canceled sales orders created for the selected customer should be deleted. This also deletes any invoiced or canceled sales orders that were created before the selected date. For example, if you enter February 1, 2014, all invoiced and canceled sales orders that were created on or before February 1, 2014 will be deleted.
    
      - In the **Invoice aged days** field, enter the number of days up to today’s date for which all invoiced and canceled sales orders should be deleted. For example, if today is April 1, 2014, and you enter 30, all invoiced or canceled sales orders created on or before March 2, 2014 will be deleted.
    
      - In the **Last invoiced through** field, select the date on which all invoiced or canceled sales orders created should be deleted. This also deletes any invoiced or canceled sales orders that were created before the selected date. For example, if you enter February 1, 2014, all invoiced and canceled sales orders that were created on or before February 1, 2014 will be deleted.

3.  Click **OK**.

## Related tasks

Create a basic sales order for Call center

[Apply payments in sales orders](apply-payments-in-sales-orders.md)

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
<td><p>Sales manager</p></td>
</tr>
</tbody>
</table>


## See also

[Mass delete quotations](mass-delete-quotations.md)

[Delete the update history of purchase or sales orders](delete-the-update-history-of-purchase-or-sales-orders.md)

[Delete orders (class form)](https://technet.microsoft.com/en-us/library/aa620155\(v=ax.60\))

  


