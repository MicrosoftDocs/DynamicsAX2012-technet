---
title: About time windows
TOCTitle: About time windows
ms:assetid: 10569991-26a5-4223-a137-df62a491cfcf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496560(v=AX.60)
ms:contentKeyID: 37832490
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About time windows [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use time windows to optimize the scheduling of service order lines. You can set up the system so that it automatically creates service orders. Based on the criteria specified by a time window, you can connect as many service order lines as possible to as few service orders as possible.

Time windows specify how far a service order line can move from its calculated date. The calculated date is the date when the service order line was scheduled to occur. The date is based on its interval setting and the service period that you defined in the **Create service orders** form. You define a time window by using the values in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Week</strong></p></td>
<td><p>The date that the service order line can be moved to any open day in the same week as the initial calculated date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Month</strong></p></td>
<td><p>The date that the service order line can be moved to any open day in the same month as the initial calculated date. For example, the calculated date for a service order line is February 15, 2012. The service order line can be scheduled for any weekday between February 1 and February 28, 2012.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Manual</strong></p></td>
<td><p>You define the maximum number of days before or after the initial calculated date that the service order line can be moved.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If you do not specify a time window for a service agreement line, the service order line that is derived from the service agreement must be on the exact date for which it was originally scheduled.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

