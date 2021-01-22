---
title: BarcodeSegmentType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BarcodeSegmentType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodesegmenttype(v=AX.60)
ms:contentKeyID: 62209975
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.ConfigDigit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.Salesperson
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.SizeDigit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.Pharmacy
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.Quantity
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.AnyNumber
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.LoyaltyCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.DiscountCode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.GiftCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.DataEntry
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.EANLicenseCode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.Item
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.StyleDigit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.Price
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.Employee
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.ColorDigit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.CheckDigit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeSegmentType.Customer
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeSegmentType Enumeration

Barcode mask segment types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration BarcodeSegmentType
'Usage
Dim instance As BarcodeSegmentType
```

``` csharp
public enum BarcodeSegmentType
```

``` c++
public enum class BarcodeSegmentType
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
<td>Item</td>
<td>If the Barcode mask type matches the Item ID.</td>
</tr>
<tr class="even">
<td></td>
<td>AnyNumber</td>
<td>If the Barcode mask type matches the Any Number.</td>
</tr>
<tr class="odd">
<td></td>
<td>CheckDigit</td>
<td>If the Barcode mask type matches the Check digit ID.</td>
</tr>
<tr class="even">
<td></td>
<td>SizeDigit</td>
<td>If the Barcode mask type matches the Size digit.</td>
</tr>
<tr class="odd">
<td></td>
<td>ColorDigit</td>
<td>If the Barcode mask type matches the Color digit.</td>
</tr>
<tr class="even">
<td></td>
<td>StyleDigit</td>
<td>If the Barcode mask type matches the Style digit.</td>
</tr>
<tr class="odd">
<td></td>
<td>EANLicenseCode</td>
<td>If the Barcode mask type matches the EAN License code.</td>
</tr>
<tr class="even">
<td></td>
<td>Price</td>
<td>If the Barcode mask type matches the Price.</td>
</tr>
<tr class="odd">
<td></td>
<td>Quantity</td>
<td>If the Barcode mask type matches the Quantity.</td>
</tr>
<tr class="even">
<td></td>
<td>Employee</td>
<td>If the Barcode mask type matches the Employee ID.</td>
</tr>
<tr class="odd">
<td></td>
<td>Customer</td>
<td>If the Barcode mask type matches the Customer ID.</td>
</tr>
<tr class="even">
<td></td>
<td>DataEntry</td>
<td>If the Barcode mask type matches the DataEntry operator ID.</td>
</tr>
<tr class="odd">
<td></td>
<td>Salesperson</td>
<td>If the Barcode mask type matches the SalesPerson ID.</td>
</tr>
<tr class="even">
<td></td>
<td>Pharmacy</td>
<td>If the Barcode mask type matches the Pharmacy.</td>
</tr>
<tr class="odd">
<td></td>
<td>ConfigDigit</td>
<td>If the Barcode mask type matches the configuration digit.</td>
</tr>
<tr class="even">
<td></td>
<td>DiscountCode</td>
<td>If the Barcode mask type matches the Discount code ID.</td>
</tr>
<tr class="odd">
<td></td>
<td>GiftCard</td>
<td>If the Barcode mask type matches the GiftCard.</td>
</tr>
<tr class="even">
<td></td>
<td>LoyaltyCard</td>
<td>If the Barcode mask type matches the Loyalty.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the RetailBarcodeMaskCharacterTypeBase base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

