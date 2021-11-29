---
title: About order entry deadlines
TOCTitle: About order entry deadlines
ms:assetid: 69192fde-5223-46e6-832f-bbf0fed1e73b
ms:mtpsurl: https://technet.microsoft.com/library/Aa571166(v=AX.60)
ms:contentKeyID: 36057961
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- entry
- sales order
- deadline
- deadlines
audience: Application User
ms.search.region: Global
---

# About order entry deadlines 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In many companies, a sales order must be received before a certain time of day for the sales order to be treated as if it is received that day. If the order is received after this deadline, the company treats the sales order as if it is received the next business day.

You set up order-entry-deadline times for all the days of the week in the **Order entry deadlines** form. If an order is received after this time, it will be treated as if it is received the next day. By default, these times are set to 23:59 – that is, one minute to midnight at the end of the relevant day. You can change the default times, so that they coincide with actual ship- or receipt-deadline times.

You can define order-entry deadlines for a specific group of customers. This could be relevant, for example, if you want to allow a group of specific customers to have order-entry deadlines that are later than those of other customers. First, you define groups for order-entry deadlines in the **Order entry deadline groups** form, and then you assign the groups to customers. You assign the groups to customers in the **Customers** form.

If your company consists of several sites, you can set up order-entry deadlines per site. If the sites are located in different time zones, the order-entry deadline is set up in the site time zone. However, when you are working with sales orders and sales quotations, the order-entry deadline is converted to your time zone in the **Available ship and receipt dates** form.

You define allowed combinations of sites and order-entry-deadline groups in the **Activate order entry deadline combinations** form.

## Example: Order-entry deadline

Today is Tuesday and the time is 17:00. If you set the order deadline to 16:00 on Tuesday and try to set the ship date as today’s date (assuming zero lead time), you will get a warning that the date is invalid if the **Delivery date control** check box is selected. This warning will appear on the **Available ship and receipt dates** form, on which you can choose alternative dates.

## Example: Different order-entry deadline per site

Your company consists of two sites. The sites are located in two different time zones.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Site A</p></th>
<th><p>Site B</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>California</p></td>
<td><p>Florida</p></td>
</tr>
<tr class="even">
<td><p>PST (Pacific Standard Time)</p></td>
<td><p>EST (Eastern Standard Time)</p></td>
</tr>
</tbody>
</table>


Sites A and B have defined the following order-entry deadlines.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Order-entry deadline</p></th>
<th><p>PST</p></th>
<th><p>Order-entry deadline</p></th>
<th><p>EST</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Monday</p></td>
<td><p>13:00</p></td>
<td><p>Monday</p></td>
<td><p>14:00</p></td>
</tr>
<tr class="even">
<td><p>Tuesday</p></td>
<td><p>13:00</p></td>
<td><p>Tuesday</p></td>
<td><p>14:00</p></td>
</tr>
<tr class="odd">
<td><p>Wednesday</p></td>
<td><p>13:00</p></td>
<td><p>Wednesday</p></td>
<td><p>14:00</p></td>
</tr>
<tr class="even">
<td><p>Thursday</p></td>
<td><p>13:00</p></td>
<td><p>Thursday</p></td>
<td><p>14:00</p></td>
</tr>
<tr class="odd">
<td><p>Friday</p></td>
<td><p>13:00</p></td>
<td><p>Friday</p></td>
<td><p>14:00</p></td>
</tr>
</tbody>
</table>


You are the order processor, and you are located in Utah, where the time zone is MST (Mountain Standard Time).

This means that as long as you place orders with site A before MST 14:00 and with site B before MST 12:00, you meet the order-entry deadlines for both sites.

The following table shows the order-entry deadlines for sites A and B, converted to MST time.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Site A (PST)</p></th>
<th><p>MST</p></th>
<th><p>Site B (EST)</p></th>
<th><p>MST</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>13:00</p></td>
<td><p>14:00</p></td>
<td><p>14:00</p></td>
<td><p>12:00</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If adjustment for daylight-saving time is in effect, the order-entry deadlines are adjusted accordingly.</P>



## Example: Same order-entry deadline per site

Your company consists of two sites. The sites are located in two different time zones.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Site A</p></th>
<th><p>Site B</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>California</p></td>
<td><p>Florida</p></td>
</tr>
<tr class="even">
<td><p>PST (Pacific Standard Time)</p></td>
<td><p>EST (Eastern Standard Time)</p></td>
</tr>
</tbody>
</table>


Sites A and B have defined the following order-entry deadlines.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Order-entry deadline</p></th>
<th><p>PST and EST</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Monday</p></td>
<td><p>13:00</p></td>
</tr>
<tr class="even">
<td><p>Tuesday</p></td>
<td><p>13:00</p></td>
</tr>
<tr class="odd">
<td><p>Wednesday</p></td>
<td><p>13:00</p></td>
</tr>
<tr class="even">
<td><p>Thursday</p></td>
<td><p>13:00</p></td>
</tr>
<tr class="odd">
<td><p>Friday</p></td>
<td><p>13:00</p></td>
</tr>
</tbody>
</table>


You are the order processor, and you are located in Utah, where the time zone is MST (Mountain Standard Time).

This means that as long as you place orders with site A before MST 14:00 and with site B before MST 11:00, you meet the order-entry deadlines for both sites.

The following table shows the order-entry deadlines for sites A and B, converted to MST time.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Site A (PST)</p></th>
<th><p>Site A (MST)</p></th>
<th><p>Site B (EST)</p></th>
<th><p>Site B (MST)</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>13:00</p></td>
<td><p>14:00</p></td>
<td><p>13:00</p></td>
<td><p>11:00</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If adjustment for daylight-saving time is in effect, the order-entry deadlines are adjusted accordingly.</P>



## See also

[About delivery dates](about-delivery-dates.md)

[Set up delivery date control](set-up-delivery-date-control.md)

[Create and manage order entry deadline groups](create-and-manage-order-entry-deadline-groups.md)

[Activate order entry deadline combinations](activate-order-entry-deadline-combinations.md)

[Set up order entry deadlines](set-up-order-entry-deadlines.md)

[Set up the transport calendar](set-up-the-transport-calendar.md)

  


