---
title: AddressFilter Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressFilter Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressfilter(v=AX.60)
ms:contentKeyID: 62214915
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter.ZipCodes
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter.Countries
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter.StateProvinces
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter.Districts
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter.Counties
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter.Cities
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter.AddressByZipCode
dev_langs:
- CSharp
- C++
- VB
---

# AddressFilter Enumeration

Represents the address filter criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration AddressFilter
'Usage
Dim instance As AddressFilter
```

``` csharp
public enum AddressFilter
```

``` c++
public enum class AddressFilter
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>No filter is specified.</td>
</tr>
<tr class="even">
<td></td>
<td>Countries</td>
<td>Specifies the Country as filter.</td>
</tr>
<tr class="odd">
<td></td>
<td>StateProvinces</td>
<td>Specifies the State provinces as filter.</td>
</tr>
<tr class="even">
<td></td>
<td>Counties</td>
<td>Specifies the counties as filter.</td>
</tr>
<tr class="odd">
<td></td>
<td>Cities</td>
<td>Specifies the cities as filter.</td>
</tr>
<tr class="even">
<td></td>
<td>ZipCodes</td>
<td>Specifies the zipcodes as filter.</td>
</tr>
<tr class="odd">
<td></td>
<td>Districts</td>
<td>Specifies the districts as filter.</td>
</tr>
<tr class="even">
<td></td>
<td>AddressByZipCode</td>
<td></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

