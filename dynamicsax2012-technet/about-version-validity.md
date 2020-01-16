---
title: About version validity
TOCTitle: About version validity
ms:assetid: 63d0b474-c75b-40be-940d-a604e9ebed3e
ms:mtpsurl: https://technet.microsoft.com/library/Aa571138(v=AX.60)
ms:contentKeyID: 36057695
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About version validity 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Active versions are the only versions used by the system outside the bill of materials (BOM) functionality. For example, **Production control** uses only active versions. Multiple active BOM and route versions can exist only if the dates do not overlap. This enables you to manipulate the BOM composition of products by using BOM versions.

## Example

If you create two BOM versions for item FLL-2500:

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>BOM</p></th>
<th><p>From date</p></th>
<th><p>To date</p></th>
<th><p>Active</p></th>
<th><p>Approved</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>216</p></td>
<td><p>January 1, 2012</p></td>
<td><p>December 31, 2012</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item number</p></th>
<th><p>Warehouse</p></th>
<th><p>Quantity</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SP-Lamp arm/Long</p></td>
<td><p>GW</p></td>
<td><p>Lamp arm Long</p></td>
</tr>
<tr class="even">
<td><p>CL-100-B</p></td>
<td><p>GW</p></td>
<td><p>Ceiling Lamp - Brushed</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>BOM</p></th>
<th><p>From date</p></th>
<th><p>To date</p></th>
<th><p>Active</p></th>
<th><p>Approved</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>217</p></td>
<td><p>January 1, 2013</p></td>
<td><p>December 31, 2013</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item number</p></th>
<th><p>Warehouse</p></th>
<th><p>Quantity</p></th>
<th><p>Item name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SP-Lamp arm/Long</p></td>
<td><p>GW</p></td>
<td><p>1</p></td>
<td><p>Lamp arm Long</p></td>
</tr>
<tr class="even">
<td><p>CL-100-C</p></td>
<td><p>GW</p></td>
<td><p>1</p></td>
<td><p>Ceiling Lamp - Chrome</p></td>
</tr>
</tbody>
</table>


From January 1 2013, the active version changes from 216 to 217 where the BOM version uses **Ceiling lamp - Chrome** instead of **Ceiling lamp - Brushed**.

You can also set up version dates in the BOM Designer. Version dates are used to detect which BOM version is the current one on a given date. The current version is displayed in the **Current BOM** field in the **BOM designer**.


> [!NOTE]
> <P>You can discontinue using a given version temporarily or permanently by using expired, or inactive, version dates, or by inactivating the version.</P>


  


