---
title: Confirm a load for shipping
TOCTitle: Confirm a load for shipping
ms:assetid: d441a41f-27c5-47c5-948f-64da00d9ba02
ms:mtpsurl: https://technet.microsoft.com/library/Dn770237(v=AX.60)
ms:contentKeyID: 62583047
author: Khairunj
ms.date: 07/11/2014
mtps_version: v=AX.60
f1_keywords:
- shipment
- confirm load
- inbound load
- outbound load
- receiving
- packing structure
- shipping document
audience: Application User
ms.search.region: Global
---

# Confirm a load for shipping 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to confirm a load for shipping. When an outbound load is confirmed, you can generate shipping documents, such as a packing slip or bill of lading to be shipped with the load. When an inbound load is confirmed, you can define a packing structure that specifies how the load should be packed. After the packing structure is defined, you can confirm the inbound load.

## This task is part of a bigger process

Confirming a load is part of the inbound or outbound processes in a warehouse. For more information, see [Business process: Planning transportation for inbound loads](business-process-planning-transportation-for-inbound-loads.md) or [Business process: Planning and processing outbound loads for shipping](business-process-planning-and-processing-outbound-loads-for-shipping.md).

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
<th><p>Prerequisites</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Outbound loads</p></td>
<td><ul>
<li><p>Create an outbound load. For more information, see <a href="create-or-modify-an-outbound-load.md">Create or modify an outbound load</a>.</p></li>
<li><p>Assign a rate, route, and shipping carrier to the outbound load.</p></li>
<li><p>Create and process a wave manually to specify the pick and put locations for a load. For more information, see <a href="create-process-and-release-a-wave-manually.md">Create, process, and release a wave manually</a>.</p></li>
<li><p>Pick, put, and pack the outbound load. For more information, see <a href="pick-put-and-pack-an-outbound-load.md">Pick, put, and pack an outbound load</a>.</p></li>
<li><p>Plan an appointment to ship the packed load to a destination. For more information, see <a href="plan-appointments-for-a-load.md">Plan appointments for a load</a>.</p></li>
<li><p>Register a driver check-in and check-out to complete an appointment for a load. For more information, see <a href="register-driver-check-in-and-check-out-for-an-appointment.md">Register driver check-in and check-out for an appointment</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Inbound loads</p></td>
<td><ul>
<li><p>Create an inbound load. For more information, see <a href="create-or-modify-an-inbound-load.md">Create or modify an inbound load</a>.</p></li>
<li><p>Assign a rate, route, and shipping carrier to the inbound load.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Confirm an outbound load and generate shipping documents

Use the **Load planning workbench** form to confirm an outbound load for shipping. After the load is confirmed, you can send an Advance Shipment Notice (ASN) to the customer. Print one or more of the following documents to be shipped with the load:

  - Bill of lading

  - Packing slip

  - Packing list

  - Commercial invoice

To confirm an outbound load and print shipping documents, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Load planning workbench**.
    
    –or–
    
    Click **Warehouse management** \> **Common** \> **Load planning workbench**.

2.  Select a load line. On the **Ship and receive** menu, click **Outbound shipment**.

3.  On the **Print** menu, select the shipping document that you want to print.

4.  Optional: On the **Print** menu, click **Send ASN** to print and send an ASN to a customer.

## Confirm an inbound load

To confirm an inbound load, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Load planning workbench**.
    
    –or–
    
    Click **Warehouse management** \> **Common** \> **Load planning workbench**.

2.  On the **Loads** FastTab, select a load line.

3.  Optional: On the **Ship and receive** menu, click **Packing structure** to define pallets, cases, and items for the inbound load that you want to receive.

4.  In the **Load planning workbench** form, on the **Ship and receive** menu, click **Inbound shipment** to confirm the inbound load.

## Related tasks

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

  


