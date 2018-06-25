---
title: Set up accessorial charges for a shipping carrier
TOCTitle: Set up accessorial charges for a shipping carrier
ms:assetid: 7252004c-5ce2-4e10-a366-1f6c30326dd8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553170(v=AX.60)
ms:contentKeyID: 62200093
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSAccessorialAssignment
- accessorial charges
- Carrier accessorial charges
- fuel charges
---

# Set up accessorial charges for a shipping carrier [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Before you can set up an accessorial assignment, you must set up accessorial masters and accessorial charges for carriers and hubs. An accessorial assignment associates a carrier with a surcharge configuration, which is used when you rate a shipment.

The fuel indexes determined by the Department of Energy (DOE) also affect the rates that you identify for a shipment. For more information about how to set up and apply fuel indexes, see [Set up carrier fuel indexes](set-up-carrier-fuel-indexes.md).

## Set up an accessorial master

The accessorial master is used to categorize the carrier accessorial and hub accessorial charges. You must set up an accessorial master before you can set up a carrier accessorial.

To set up an accessorial master, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Accessorial master**.

2.  Click **New**.

3.  Enter an ID and a descriptive name for the accessorial master.

4.  In the **Accessorial type** field, select either **Shipping carrier** or **Hub**.

## Set up a carrier accessorial

Associate a shipping carrier with information such as a carrier service, an accessorial master, and a billing group.

To set up a carrier accessorial, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Carrier accessorial charges**.

2.  Click **New**.

3.  Enter an ID for the carrier accessorial.

4.  Specify the carrier details for the accessorial charges, such as shipping carrier ID, carrier service, accessorial master ID, external code of the carrier service, and billing group ID.

5.  In the **Accessorial delivery type** field, select an accessorial delivery type for the carrier.

6.  Click **Accessorial assignments** to define parameters for the accessorial assignment and to define how the accessorial charges are calculated. For more information, see [Set up accessorial assignments](set-up-accessorial-assignments.md).

## Set up a hub master

The hub master is used to categorize the hub, such as a warehouse or port. You must set up a hub master before you can set up hub accessorial charges.

To set up a hub master, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Routing** \> **Hub master**.

2.  Click **New**.

3.  In the **Hubs** field, enter an ID for the hub.

4.  On the **Codes** tab, in the **Hub type** field, select identification for the hub type.

5.  Optional: In the **Rates** field, select a rate master.

6.  Optional: On the **Effective dates** tab, provide information about periods where the hub rate applies.

7.  Optional: On the **Address** and **Additional vendor contact information** tabs, provide an address and additional vendor contact information.

## Set up hub accessorial charges

Associate a hub with information such as a billing group and specify the hub for either pickup or delivery.

To set up hub accessorial charges, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Hub accessorial charges**.

2.  Click **New**.

3.  Enter an ID for the hub accessorial.

4.  Specify the hub details for accessorial charges, such as hub ID, hub position, external code of a carrier service, billing group ID, and accessorial master ID.

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
<td><p><strong>Configuration key</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>


## See also

[Set up accessorial assignments](set-up-accessorial-assignments.md)

[Set up carrier fuel indexes](set-up-carrier-fuel-indexes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

