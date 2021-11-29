---
title: BarcodeMaskType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BarcodeMaskType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemasktype(v=AX.60)
ms:contentKeyID: 62212057
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.Coupon
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.Customer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.DiscountCode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.DataEntry
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.Item
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.LoyaltyCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.Salesperson
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.Employee
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.GiftCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType.Pharmacy
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeMaskType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Describes the internal type of the barcode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration BarcodeMaskType
'Usage
Dim instance As BarcodeMaskType
```

``` csharp
public enum BarcodeMaskType
```

``` c++
public enum class BarcodeMaskType
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
<td>If the Barcode does not match with any type.</td>
</tr>
<tr class="even">
<td></td>
<td>Item</td>
<td>If the Barcode matches an Item.</td>
</tr>
<tr class="odd">
<td></td>
<td>Customer</td>
<td>If the Barcode matches the customer number.</td>
</tr>
<tr class="even">
<td></td>
<td>Employee</td>
<td>If the Barcode matches the Employee ID.</td>
</tr>
<tr class="odd">
<td></td>
<td>Coupon</td>
<td>If the Barcode matches the Discount coupon.</td>
</tr>
<tr class="even">
<td></td>
<td>DataEntry</td>
<td>If the Barcode matches the DataEntry.</td>
</tr>
<tr class="odd">
<td></td>
<td>Salesperson</td>
<td>If the Barcode matches the Salesperson.</td>
</tr>
<tr class="even">
<td></td>
<td>Pharmacy</td>
<td>If the Barcode matches the Pharmacy.</td>
</tr>
<tr class="odd">
<td></td>
<td>DiscountCode</td>
<td>If the Barcode matches the Discount code.</td>
</tr>
<tr class="even">
<td></td>
<td>GiftCard</td>
<td>If the Barcode matches the Gift card number.</td>
</tr>
<tr class="odd">
<td></td>
<td>LoyaltyCard</td>
<td>If the Barcode matches the Loyalty number.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the RetailBarcodeMaskTypeBase base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

