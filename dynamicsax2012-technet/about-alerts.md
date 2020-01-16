---
title: About alerts
TOCTitle: About alerts
ms:assetid: 7116a93b-2d76-48af-835d-5a990e616d9c
ms:mtpsurl: https://technet.microsoft.com/library/Aa571310(v=AX.60)
ms:contentKeyID: 46687550
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About alerts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Alerts form a notification system for critical events in Microsoft Dynamics AX. You can use alerts to stay informed about events that you want to keep track of during the workday.

You can easily set up your own set of rules so that you are alerted about overdue deliveries, orders that are deleted, prices that change, or other events that you must respond to.

## What occurs when an alert rule is created?

When you create alert rules, you can associate a predefined event with a field. For example, when the date that is specified in the field occurs, or when the contents of a field change. Alternatively, you can associate an event with the records in a particular form. For example, when the record is created or deleted.

When the selected event occurs for that field, or a record in that form, an alert is sent to you. For example, you create a rule in which you associate the **Delivery date** field on a specific purchase order line with the **was due this amount of time ago** event. You set the time frame to five days. In this example, an alert is triggered five days after the delivery date of that purchase order line.

Additionally, you can refine the alert rules by setting conditions. For example, you can be alerted about new purchase orders that are created for specific vendor accounts.

## See also

[Access alerts](access-alerts.md)

  


