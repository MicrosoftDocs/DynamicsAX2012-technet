---
title: SalesInvoiceType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesInvoiceType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoicetype(v=AX.60)
ms:contentKeyID: 62204564
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType.ItemRequirements
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType.Quotation
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType.Journal
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType.Blanket
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType.Subscription
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType.ReturnItem
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType.Sales
dev_langs:
- CSharp
- C++
- VB
---

# SalesInvoiceType Enumeration

Represents the type of sales invoice journal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration SalesInvoiceType
'Usage
Dim instance As SalesInvoiceType
```

``` csharp
[DataContractAttribute]
public enum SalesInvoiceType
```

``` c++
[DataContractAttribute]
public enum class SalesInvoiceType
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
<td>Journal</td>
<td>Journal sales type.</td>
</tr>
<tr class="even">
<td></td>
<td>Quotation</td>
<td><strong>Obsolete.</strong> Quotation sales type.</td>
</tr>
<tr class="odd">
<td></td>
<td>Subscription</td>
<td>Subscription sale type.</td>
</tr>
<tr class="even">
<td></td>
<td>Sales</td>
<td>Sales sale type.</td>
</tr>
<tr class="odd">
<td></td>
<td>ReturnItem</td>
<td>ReturnItem sale type.</td>
</tr>
<tr class="even">
<td></td>
<td>Blanket</td>
<td><strong>Obsolete.</strong> Blanket sale type.</td>
</tr>
<tr class="odd">
<td></td>
<td>ItemRequirements</td>
<td>Item requirements sale type.</td>
</tr>
</tbody>
</table>


## Remarks

In AX, this is represented as SalesType base enum.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

