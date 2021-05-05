---
title: About alert rules
TOCTitle: About alert rules
ms:assetid: 8d3901d5-42de-44ff-a4df-19207e358afc
ms:mtpsurl: https://technet.microsoft.com/library/Aa498338(v=AX.60)
ms:contentKeyID: 46687555
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About alert rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you set up an alert rule, decide when or in what situations you want to receive alerts. When you know which event you want to be notified about, you can locate the form where the data that causes the event is displayed in Microsoft Dynamics AX. The event can be a date that arrives or a change that occurs. Therefore, you must find the Microsoft Dynamics AX form where this date is specified, or where the field that changes or the new record is displayed. When you have this information, you can create your alert rule.

When you create an alert rule, you define the criteria that the system must meet before an alert is triggered. You can think of criteria as a match between the occurrence of an event and the fulfillment of specific conditions. When an event occurs, the system starts to perform a check according to the conditions that are set up in Microsoft Dynamics AX.

## Events

The event that triggers an alert rule can be a date that arrives or a specific change that occurs. Events are defined in the **Send email alerts for job status changes** area of the **Create alert rule** form. The events that are available for a particular field depend on that field.

For example, if you want to set up an alert rule for the **Start date** field, due date events are appropriate. Therefore, the **is due in** event type is available for this field. However, for a field such as **Cost center**, a due date event is not appropriate, so that the **is due in** event type is not available. However, the **has changed** event type is available.

## Event types

Three types of events can occur:

  - [Due date-type events](due-date-type-events.md) – These events trigger an alert when a date arrives.

  - [Update-type events](update-type-events.md) – These events trigger an alert when data in a particular field changes.

  - [Create-type and delete-type events](create-type-and-delete-type-events.md) – These events trigger an alert when a record is created or deleted.

Changes that occur can be initiated by a user. For example, the user changes the delivery date of a purchase order. Alternatively, changes can occur as part of a process. For example, the **Status** field of a form changes to reflect the life cycle of various processes in the system.

## Conditions

In the **Alert me for** area of the **Create alert rule** form, you can use conditions to control when you are alerted about events. For example, you can specify that the system should alert you when the status of purchase orders change, but only if a purchase order matches a certain set of conditions.

In this case, you want to be alerted when the status of purchase orders are set to **Received**. This change in status is the event that triggers the alert.

Then, you must decide which purchase orders you want to be alerted about. For example, you can select one of the following options. These options define the conditions for the alert rule.

  - **All records in %1** – You receive alerts when the status of any purchase order changes to received.

  - **Current record in %1%2** – You receive an alert when the status of a specific purchase order changes to received.

  - **Only records in %1 that match the selected filter** – You receive an alert when the status of a purchase order that is limited by specific criteria changes to received. If you select this option, you can use the query functionality in an **Inquiry** form in Microsoft Dynamics AX to set up your conditions in a very flexible manner.

## Expiry of rule

In the **Alert me until** area of the **Create alert rule** form, you can specify how long you want the alert rule to be active.

## Alert contents

In the **Alert me with** area of the **Create alert rule** form, you can specify the subject text and message text that you want the alert messages to use.

## User ID

In the **Alert who** area of the **Create alert rule** form, you can specify which user you want to receive the alert messages. By default, your user ID is selected.

## Delivery method

In the **Other alerts** area of the **Create alert rule** form, you can specify whether you want your alerts to be delivered as pop-up messages or email messages.


> [!NOTE]
> <P>You can disable the options for email messages and the pop-up messages in the <STRONG>Options...</STRONG> form. If you disable these options, the options are not available in the <STRONG>Create alert rule</STRONG> form.</P>



## See also

[Create alert rules](create-alert-rules.md)

[Manage alert rules](manage-alert-rules.md)

  


