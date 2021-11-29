---
title: Set up a transportation status
TOCTitle: Set up a transportation status
ms:assetid: 76836936-7a2a-47e3-8f84-a15c5fe9f1b8
ms:mtpsurl: https://technet.microsoft.com/library/Dn553171(v=AX.60)
ms:contentKeyID: 62200096
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSTransportationStatus
- Forms.TMSTransportationStatusMaster
- transportation status
- transportation statuses
audience: Application User
ms.search.region: Global
---

# Set up a transportation status 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up transportation status master codes and how to map a master code to the status codes of a shipping carrier. For example, you can use transportation master codes to interpret the codes from a shipping carrier to determine that the shipment status is Delivered.

## Set up a transportation status master code

Set up master codes for transportation statuses to interpret codes provided by shipping carriers. The transportation status that you provide for a transportation master status code can help you track the status of a load, shipment, or container.

To set up a transportation status master code, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Transportation status master**.

2.  Click **New** to create a transportation status master.

3.  In the **Transportation status master** field, enter a unique code for the transportation status.

4.  In the **Transportation type** field, select either the **Shipping carrier** or **Hub** option as the type of transportation.

5.  Enter a description and name for the transportation status.

## Map a transportation status master code to a code from a shipping carrier

By mapping transportation status master codes to individual codes of a shipping carrier, you associate the status codes of the shipping carrier with the status messages that you want to use.

To map a transportation status master code to a code from a shipping carrier, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Carrier transportation status**.

2.  Click **New** to map a code from a shipping carrier to a transportation status master code.

3.  Select the unique ID for the shipping carrier and the carrier service.

4.  Select the transportation status code that you want to map to the selected shipping carrier’s code.

5.  Enter the external code that is used by the shipping carrier.

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

  


