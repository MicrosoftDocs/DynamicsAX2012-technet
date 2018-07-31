---
title: Set up a transportation mode and method for a shipping carrier
TOCTitle: Set up a transportation mode and method for a shipping carrier
ms:assetid: 3da6501e-c40f-4253-951a-932e6f3526de
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553160(v=AX.60)
ms:contentKeyID: 62200057
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSMethod
- Forms.TMSMode
- transportation method
- transportation methods
- transportation mode
- transportation modes
audience: Application User
ms.search.region: Global
---

# Set up a transportation mode and method for a shipping carrier 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



You can associate a transportation mode and a transportation method with a shipping carrier to determine the carrier rates and routes for loads of freight.

## Set up a transportation mode for a shipping carrier

The transportation mode represents the form of transport that the carrier uses for freight deliveries, such as Less than truckload (LTL), Truckload (TL), or Parcel. A carrier can be associated with one or more transportation modes.

To create a transportation mode for a shipping carrier, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Mode**.

2.  Click **New** to create a new mode.

3.  Enter a unique ID and a descriptive name for the mode.

To associate a shipping carrier with a transportation mode, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Shipping carrier**.

2.  In the **Mode** field, select a transportation mode.

## Set up a transportation method for a shipping carrier

The transportation method represents the form of transport that the carrier uses for freight deliveries, such as air, ground, ocean, or rail. A carrier can be associated with an unlimited number of transportation methods.

To create a transportation method for a shipping carrier, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Transportation method**.

2.  Click **New** to create a new transportation method.

3.  Enter a unique ID and descriptive name for the transportation method.

To associate a shipping carrier with a transportation method, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Shipping carrier**.

2.  Select a shipping carrier. On the **Service** FastTab, click **New** to create a new line.

3.  In the **Transportation method** field, select a transportation method.

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

[Set up shipping carriers and carrier groups](set-up-shipping-carriers-and-carrier-groups.md)

  


