---
title: About delivery schedules
TOCTitle: About delivery schedules
ms:assetid: 707ed6e5-2f41-47ae-bf57-95d241cfc2e5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242647(v=AX.60)
ms:contentKeyID: 36058056
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- schedule
- deliver in batches
- delivery schedule
- delivery line
- delivery
- order line
- track deliveries
- schedule deliveries
- delivery schedules
audience: Application User
ms.search.region: Global
---

# About delivery schedules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the delivery schedule functionality when you want to split a sales order, purchase order, or sales quotation order line into several order lines. Each order line is called a delivery line. Two or more delivery lines make up one delivery schedule. The delivery lines can vary in delivery dates, quantities, mode of delivery, and storage dimensions such as site and warehouse.

**Example of a deliver schedule for an order of 600 chairs**

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Total order (original order line)</p></td>
<td><p>600 chairs</p></td>
</tr>
<tr class="even">
<td><p>Requested delivery schedule</p></td>
<td><p>100 chairs per month</p></td>
</tr>
<tr class="odd">
<td><p>Requested delivery timeframe</p></td>
<td><p>6 months, on the first of each month</p></td>
</tr>
</tbody>
</table>


In this scenario, the customer requests a delivery of 600 chairs in batches of 100 chairs over a period of six months. To keep track, create a delivery schedule. On the delivery schedule form, you create six separate delivery lines. Each delivery line will contain 100 chairs and indicate the delivery date for those 100 chairs. In this case, each line will be offset on the first of the month for six consecutive months.

On a delivery schedule, you can view and change the status of each delivery line in the context of the associated deliveries. You can keep track of deliveries that have been posted with a packing slip or product receipt, and you can track what has been delivered or received and what is still pending. Also, if a trade agreement that has a defined total order discount exists, the delivery schedule ensures that your order is eligible for the total order discount, even when it is split into separate deliveries.

When you create a delivery schedule, the original order line is automatically converted into an order line that has multiple deliveries, and it is indicated on the line by an icon.


> [!NOTE]
> <P>In these areas of Microsoft Dynamics AX, only the delivery lines are shown:</P>
> <UL>
> <LI>
> <P>In Enterprise Portal for Microsoft Dynamics AX</P>
> <LI>
> <P>When you post</P>
> <LI>
> <P>When you copy forms</P>
> <LI>
> <P>When you browse list pages and reports</P></LI></UL>



When you confirm a sales quotation, the whole delivery schedule – including the order line with multiple deliveries – is displayed on the resulting sales order. In addition, the whole delivery schedule is displayed in all the major forms, such as sales orders, sales quotations, and purchase orders.

## See also

[About sales delivery schedules](about-sales-delivery-schedules.md)

[Purchase delivery schedules](purchase-delivery-schedules.md)

[About quotation delivery schedules](about-quotation-delivery-schedules.md)

  


