---
title: ItemAvailabilityPreferences Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemAvailabilityPreferences Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitypreferences(v=AX.60)
ms:contentKeyID: 49824364
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences.ChannelSite
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences.ChannelWarehouse
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences.CustomerSite
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences.CustomerWarehouse
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences.ItemSite
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences.ItemWarehouse
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences.None
dev_langs:
- CSharp
- C++
- VB
---

# ItemAvailabilityPreferences Enumeration

Item availability preferences.

This enumeration has a [FlagsAttribute](https://technet.microsoft.com/library/dk06fkbc\(v=ax.60\)) attribute that allows a bitwise combination of its member values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
<FlagsAttribute> _
Public Enumeration ItemAvailabilityPreferences
'Usage
Dim instance As ItemAvailabilityPreferences
```

``` csharp
[DataContractAttribute]
[FlagsAttribute]
public enum ItemAvailabilityPreferences
```

``` c++
[DataContractAttribute]
[FlagsAttribute]
public enum class ItemAvailabilityPreferences
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
<td>No item availability preference.</td>
</tr>
<tr class="even">
<td></td>
<td>ChannelSite</td>
<td>Channel site preference.</td>
</tr>
<tr class="odd">
<td></td>
<td>ChannelWarehouse</td>
<td>Channel warehouse preference.</td>
</tr>
<tr class="even">
<td></td>
<td>ItemSite</td>
<td>Item site preference.</td>
</tr>
<tr class="odd">
<td></td>
<td>ItemWarehouse</td>
<td>Item warehouse preference.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerSite</td>
<td>Customer warehouse preference.</td>
</tr>
<tr class="odd">
<td></td>
<td>CustomerWarehouse</td>
<td>Customer site preference.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

