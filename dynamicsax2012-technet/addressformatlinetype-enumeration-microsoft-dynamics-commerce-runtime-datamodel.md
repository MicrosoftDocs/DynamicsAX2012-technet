---
title: AddressFormatLineType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressFormatLineType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformatlinetype(v=AX.60)
ms:contentKeyID: 49830251
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.BuildingCompliment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.City
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.CountryOKSMCode_RU
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.CountryRegion
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.County
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.District
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.Flat_RU
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.Postbox
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.State
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.StreetNumber
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.StreetName
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.ZipCode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormatLineType.House_RU
dev_langs:
- CSharp
- C++
- VB
---

# AddressFormatLineType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the address format line type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration AddressFormatLineType
'Usage
Dim instance As AddressFormatLineType
```

``` csharp
[DataContractAttribute]
public enum AddressFormatLineType
```

``` c++
[DataContractAttribute]
public enum class AddressFormatLineType
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
<td>No address format line type specified.</td>
</tr>
<tr class="even">
<td></td>
<td>ZipCode</td>
<td>The zip code.</td>
</tr>
<tr class="odd">
<td></td>
<td>City</td>
<td>The city name.</td>
</tr>
<tr class="even">
<td></td>
<td>County</td>
<td>The county name.</td>
</tr>
<tr class="odd">
<td></td>
<td>State</td>
<td>The state name.</td>
</tr>
<tr class="even">
<td></td>
<td>CountryRegion</td>
<td>The country/region name.</td>
</tr>
<tr class="odd">
<td></td>
<td>StreetName</td>
<td>The street name.</td>
</tr>
<tr class="even">
<td></td>
<td>District</td>
<td>The district name.</td>
</tr>
<tr class="odd">
<td></td>
<td>StreetNumber</td>
<td>The street number.</td>
</tr>
<tr class="even">
<td></td>
<td>BuildingCompliment</td>
<td>The building compliment.</td>
</tr>
<tr class="odd">
<td></td>
<td>Postbox</td>
<td>The P.O. box.</td>
</tr>
<tr class="even">
<td></td>
<td>House_RU</td>
<td>The house (Russia).</td>
</tr>
<tr class="odd">
<td></td>
<td>Flat_RU</td>
<td>The flat (Russia).</td>
</tr>
<tr class="even">
<td></td>
<td>CountryOKSMCode_RU</td>
<td>The country code (Russia).</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the LogisticsAddressElement enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

