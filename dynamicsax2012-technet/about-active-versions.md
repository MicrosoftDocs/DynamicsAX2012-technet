---
title: About active versions
TOCTitle: About active versions
ms:assetid: a75211a3-2726-434a-b951-5880d2fb7c61
ms:mtpsurl: https://technet.microsoft.com/library/Aa550304(v=AX.60)
ms:contentKeyID: 36058876
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About active versions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Active versions are the only versions that the system uses outside of the bill of materials (BOM) functionality. **Production control**, for example, uses only active versions. You can also set up version dates by using the **BOM designer** form.

If you want to stop using a certain version temporarily or permanently, you can assign expired or inactive version dates, or you can just inactivate the version.

Multiple active BOM and route versions can exist at the same time, as long as their dates do not overlap. This enables you to adjust the BOM’s composition of products.

## Example: using multiple active BOM versions

The following tables contain information about item FLL-2500, which is a lamp. A new BOM version is created when the material that is used to produce the lamp is changed from brushed steel to chrome, which correspond respectively to version 216 and version 217. The new version becomes active after the specified date, which is 01-01-2007.

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
<td><p>01-01-2006</p></td>
<td><p>31-12-2006</p></td>
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
<td><p>Lamp arm - long</p></td>
</tr>
<tr class="even">
<td><p>CL-100-B</p></td>
<td><p>GW</p></td>
<td><p>Ceiling lamp – brushed</p></td>
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
<td><p>01-01-2007</p></td>
<td><p>31-12-2007</p></td>
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
<td><p>Lamp arm - long</p></td>
</tr>
<tr class="even">
<td><p>CL-100-C</p></td>
<td><p>GW</p></td>
<td><p>1</p></td>
<td><p>Ceiling lamp – chrome</p></td>
</tr>
</tbody>
</table>

  


