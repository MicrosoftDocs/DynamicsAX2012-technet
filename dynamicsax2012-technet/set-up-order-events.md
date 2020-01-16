---
title: Set up order events
TOCTitle: Set up order events
ms:assetid: c6261c6f-c127-43d3-a820-19c3270b233b
ms:mtpsurl: https://technet.microsoft.com/library/Dn497826(v=AX.60)
ms:contentKeyID: 62221426
author: Khairunj
ms.date: 04/23/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up order events 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up *order events* to track actions that users take in relation to various types of customer orders. You can use order event tracking for auditing purposes, to review the actions that are taken against an order during the order’s life cycle, or to track the actions of a specific user. For example, you can record the action every time a user creates a sales order, places a hold on an order, overrides a charge, or updates an order line. You can set up order events to track actions for specific users, groups of users, or all users during a specific period of time. You can view the actions that were taken on a document by opening the **Order events** form from the **Action Pane** in the specific document form.

You can set up order events to track actions that are completed for the following document types:

  - Sales orders

  - Return orders

  - Sales quotations

  - Direct delivery orders

  - Automatic notifications and cancellations

## Set up order events

1.  Click **Sales and marketing** \> **Setup** \> **Events** \> **Order events**.

2.  In the **Order event setup** form, click **Create a new record**.

3.  In the **User code** field, select whether to apply the order event to specific users, groups of users, or all users.

4.  If appropriate, in the **User relation** field, select who the order event should be applied to, based on the selection in the **User code** field.

5.  Enter a start date and end date for the time period during which the order event should be applied.

6.  On each FastTab, select the actions that trigger an event, or click **Select all** to select all actions.

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
<td><p>Sales Manager, System administrator</p></td>
</tr>
</tbody>
</table>

  


