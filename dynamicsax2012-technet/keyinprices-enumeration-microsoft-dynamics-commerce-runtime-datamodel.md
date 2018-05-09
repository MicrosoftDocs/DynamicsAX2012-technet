---
title: KeyInPrices Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyInPrices Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.keyinprices(v=AX.60)
ms:contentKeyID: 62201911
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices.MustKeyInNewPrice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices.MustKeyInEqualHigherPrice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices.NotMandatory
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices.MustKeyInEqualLowerPrice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInPrices.EnteringPriceNotAllowed
dev_langs:
- CSharp
- C++
- VB
---

# KeyInPrices Enumeration

KeyInPrices are used when items needs to be explicitely Keyed In during the Barcode scan operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration KeyInPrices
'Usage
Dim instance As KeyInPrices
```

``` csharp
public enum KeyInPrices
```

``` c++
public enum class KeyInPrices
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
<td>NotMandatory</td>
<td>Enum value for Not Mandatory.</td>
</tr>
<tr class="even">
<td></td>
<td>MustKeyInNewPrice</td>
<td>Must Key In New Price.</td>
</tr>
<tr class="odd">
<td></td>
<td>MustKeyInEqualHigherPrice</td>
<td>Must Key In Equal/ Higher Price.</td>
</tr>
<tr class="even">
<td></td>
<td>MustKeyInEqualLowerPrice</td>
<td>Must Key In Equal/ Lower Price.</td>
</tr>
<tr class="odd">
<td></td>
<td>EnteringPriceNotAllowed</td>
<td>Entering Price is Not Allowed.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

