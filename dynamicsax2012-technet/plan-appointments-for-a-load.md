---
title: Plan appointments for a load
TOCTitle: Plan appointments for a load
ms:assetid: 9aec1151-db0d-4333-8e63-323a898fa725
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553185(v=AX.60)
ms:contentKeyID: 62221422
ms.date: 07/11/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSLoadPlanningWorkbench
- Forms.TMSAppointment
- Forms.TMSDriverLogListPage
- appointment scheduling
- driver check-in
- driver check-out
- warehouse appointments
---

# Plan appointments for a load 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Warehouse appointments represent events that occur at a dock for receiving a purchase order, shipping a sales order, or processing an inbound or outbound load at a specific date and time. Appointments are created to reduce the manual work for warehouse personnel. This helps make sure that there is availability of docks for the loading and unloading of goods, and avoids a situation in which multiple carriers arrive at a location at the same time.

## This task is part of a bigger process

Planning appointments for a load can be part of the inbound or outbound processes in a warehouse.

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
<td><p>Set up an appointment type in the <strong>Appointment types</strong> form. For more information, see <a href="set-up-appointment-scheduling-parameters.md">Set up appointment scheduling parameters</a>.</p></td>
</tr>
</tbody>
</table>


## Schedule appointments for a specific load

You can use the **Appointment scheduling** form to schedule, track, and cancel appointments for a specific load. The appointment type determines the type of location for which the appointments are created. For example, you can specify whether a particular appointment is created for an inbound or outbound dock.

When you cancel an existing appointment, you must select a reason code to specify the reason for cancellation.

To schedule an appointment for a specific load, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Load planning workbench**.

2.  On the **Loads** FastTab, select a load transaction line.

3.  On the **Transportation** menu, click **Appointment scheduling**.

4.  Create a new appointment.

5.  In the **Appointment type** field, select the identifier (ID) for the appointment type.

6.  In the **Item movement direction** field, select the direction of the shipment. You can specify whether the direction is inbound, outbound, or both.

7.  In the **Appointment status** field, select the status of the appointment.

8.  On the **Shipping details** FastTab, and then specify the details that you want to include in the appointment schedule, by using the fields that are listed in the following table.
    
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
    <td><p><strong>Appointment site</strong></p></td>
    <td><p>Select the ID for the site where the appointment will occur.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Warehouse</strong></p></td>
    <td><p>Select the ID for the warehouse where the appointment will occur.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Shipping carrier</strong></p></td>
    <td><p>Select the ID for the carrier that will transport and deliver the load.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Broker ID</strong></p></td>
    <td><p>Select the ID for the broker who booked the transaction.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Allow customer to pick up</strong></p></td>
    <td><p>Select this check box to allow the customer to pick up the shipment.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tractor number</strong></p></td>
    <td><p>Enter the ID for the tractor that is associated with the appointment.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Trailer number</strong></p></td>
    <td><p>Enter the ID for the trailer that is associated with the appointment.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Warehouse location</strong></p></td>
    <td><p>Select the warehouse location that is reserved for the appointment.</p></td>
    </tr>
    </tbody>
    </table>


9.  On the **Date and time** FastTab, enter the start date and end date of the appointment for a load at the specified location.

10. On the **Reference** FastTab, in the **Reference type** field, select the type of reference for the appointment.
    

    > [!NOTE]
    > <P>Select <STRONG>None</STRONG> to indicate that the appointment is not related to a reference document.</P>



11. In the **Reference number** field, select the ID for the sales order, purchase order, or load that you want to associate with the appointment.

12. In the **Notes** field, enter any additional information that you want to add for the appointment.

13. On the **Appointment status** menu, click **Firm the appointment** to confirm the appointment status.

## Create an instant appointment

To create an appointment quickly in the **Driver check-in and check-out** form, follow these steps:

1.  Click **Transportation management** \> **Common** \> **Driver check-in and check-out**.

2.  Click **Schedule instant appointments**.

3.  In the **Appointment type** field, select the identifier for the appointment type.

4.  Click **OK** to create an instant appointment.

## Next step

After you schedule an appointment, you can register the check-in and check-out times of drivers for an appointment.

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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

