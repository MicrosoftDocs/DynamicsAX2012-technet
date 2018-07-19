---
title: Register driver check-in and check-out for an appointment
TOCTitle: Register driver check-in and check-out for an appointment
ms:assetid: 0a85ef94-19c8-429f-8078-02bff3ef232d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn770229(v=AX.60)
ms:contentKeyID: 62583043
ms.date: 07/11/2014
mtps_version: v=AX.60
f1_keywords:
- driver check-in
- appointment
- check-out
audience: Application User
ms.search.region: Global
---

# Register driver check-in and check-out for an appointment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Driver check-in and check-out is used to start and complete an appointment for a load at a warehouse location. This topic explains how to register a driver check-in and check-out using Microsoft Dynamics AX on a computer or a mobile device.

## This task is part of a bigger process

Driver check-in and check-out can be part of the inbound or outbound processes in a warehouse. For more information, see [Business process: Planning and processing outbound loads for shipping](business-process-planning-and-processing-outbound-loads-for-shipping.md) or [Business process: Planning transportation for inbound loads](business-process-planning-transportation-for-inbound-loads.md).

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
<td><p>Setup</p></td>
<td><ol>
<li><p>Create a menu item for driver check-in and check-out in the <strong>Mobile device menu items</strong> form. For more information, see <a href="configure-mobile-devices-for-warehouse-work.md">Configure mobile devices for warehouse work</a>.</p></li>
<li><p>Set up a menu for the mobile device. For more information, see <a href="set-up-mobile-device-menus-to-display-work-or-activities.md">Set up mobile device menus to display work or activities</a>.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Precondition</p></td>
<td><p>Create an appointment for a load at a warehouse location. For more information, see <a href="plan-appointments-for-a-load.md">Plan appointments for a load</a>.</p></td>
</tr>
</tbody>
</table>


## Register driver check-in and check-out using Microsoft Dynamics AX on a computer

To register the check-in time of a driver for an appointment, follow these steps:

1.  Click **Transportation management** \> **Common** \> **Driver check-in and check-out**.

2.  Select an appointment with a status of **Firmed**.

3.  On the **Action Pane**, in the **Driver check-in details** group, click **Driver check-in and check-out details**.

4.  Click **Appointment check-in**, and specify the shipping carrier ID, trailer number, tractor number, driver name, and license number.

5.  Click **OK** to register the driver check-in time and start the appointment. The status of the appointment is updated to **Checked in**.

To register the check-out time of a driver for an appointment, follow these steps:

1.  In the **Driver check-in and check-out** form, select an appointment with a status of **Checked in**.

2.  On the **Action Pane**, in the **Driver check-in details** group, click **Driver check-in and check-out details**.

3.  Optional: Click **Appointment check-out**. You can make corrections to the shipping carrier ID, trailer number, tractor number, driver name, and license number.

4.  Click **OK** to register the driver check-out and complete the appointment. The status of the appointment is updated to **Completed**.

## Register driver check-in and check-out using Microsoft Dynamics AX on a mobile device


> [!NOTE]
> <P>This procedure is performed by using a mobile device. The information that must be provided on the mobile device varies, depending on how the device is configured. The worker who is performing the work can follow the instructions that are displayed on the mobile device to enter the required information.</P>



After you have created and confirmed an appointment in Microsoft Dynamics AX, you can register the check-in and check-out time using a mobile device. During a driver check-in, you can verify the weight and the shipping destination for an appointment, and change the shipping carrier, if it is required.

The following example shows how you can register the driver check-in time for an appointment:

1.  On the mobile device menu, select the option for driver check-in.

2.  Register and confirm the load ID, shipment ID, or appointment ID that is related to the check-in that you want to process.

## Related tasks

[Confirm a load for shipping](confirm-a-load-for-shipping.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


