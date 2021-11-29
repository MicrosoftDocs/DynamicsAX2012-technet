---
title: Set up appointment scheduling parameters
TOCTitle: Set up appointment scheduling parameters
ms:assetid: cdb696f1-5022-4409-95df-bcfec292f14b
ms:mtpsurl: https://technet.microsoft.com/library/Dn553201(v=AX.60)
ms:contentKeyID: 62200161
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSLoadPlanningWorkbench
- Classes.TMSAppointmentNotifications
- Forms.TMSParameters
- Forms.TMSCalendarType
- MsDynAx060.Forms.TMSCalendarType
- MsDynAx060.Forms.TMSParameters
- MsDynAx060.Forms.WHSLoadPlanningWorkbench
- appointment notifications
- appointment scheduling
- dock capacity
- driver check-in
- driver check-out
- freight transportation vehicles
audience: Application User
ms.search.region: Global
---

# Set up appointment scheduling parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up parameters for appointment scheduling. You must set up appointment types to create an appointment schedule for a warehouse. You can send periodic notifications for scheduled appointments.

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
<td><p>Related set up task</p></td>
<td><p>Specify the <strong>Default duration</strong> and <strong>Alert interval</strong> fields in the <strong>Transportation management parameters</strong> form.</p></td>
</tr>
</tbody>
</table>


## Set up the appointment type and appointment duration for a warehouse

To set up the appointment type, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Appointment scheduling** \> **Appointment types**.

2.  Click **New** to create a new appointment type.

3.  Enter the appointment type, site, warehouse, and location profile ID.

4.  Specify additional details for the appointment type by using the fields described in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Duration</strong></p></td>
    <td><p>Enter the appointment duration for a specified warehouse location, in minutes.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number of calendar slots</strong></p></td>
    <td><p>Enter the number of appointments that can be performed at the same time for the specified appointment type.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Item movement direction</strong></p></td>
    <td><p>Select <strong>Both</strong>, <strong>Inbound</strong>, or <strong>Outbound</strong> to indicate the direction of item movement.</p></td>
    </tr>
    </tbody>
    </table>


5.  Optional: Select the **Driver check in required** check box to indicate that a driver check-in is required before a shipment is confirmed.

## Optional: Set up appointment notifications

Use the **Appointment notifications** form to set up the appointment notification as a batch job to track the upcoming appointments.

1.  Click **Transportation management** \> **Periodic** \> **Appointment notifications**.

2.  In the **Appointment notifications** form, create or modify the recurrence and setup alerts for the batch job.

## Next step

[Plan appointments for a load](plan-appointments-for-a-load.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and then select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


