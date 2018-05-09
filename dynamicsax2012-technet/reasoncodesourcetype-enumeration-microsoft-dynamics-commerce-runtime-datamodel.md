---
title: ReasonCodeSourceType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonCodeSourceType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodesourcetype(v=AX.60)
ms:contentKeyID: 62215008
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.VoidTransaction
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.OverridePrice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.SerialNumber
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.TransactionTaxChange
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.StartOfTransaction
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.TotalDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.Markup
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.ItemNotOnFile
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.EndOfTransaction
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.VoidItem
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.LineItemTaxChange
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.VoidPayment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.ReturnItem
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.AddSalesperson
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.NegativeAdjustment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.TenderDeclaration
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.ReturnTransaction
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.ItemDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.NfcEContingencyModeEnabled
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.NfcEVoided
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType.OpenDrawer
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeSourceType Enumeration

The reason code source type enum. Maps to the available reason code source types in the source type to id mappings in the POS functionality profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ReasonCodeSourceType
'Usage
Dim instance As ReasonCodeSourceType
```

``` csharp
[DataContractAttribute]
public enum ReasonCodeSourceType
```

``` c++
[DataContractAttribute]
public enum class ReasonCodeSourceType
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
<td>The default source type.</td>
</tr>
<tr class="even">
<td></td>
<td>AddSalesperson</td>
<td>The add sales person.</td>
</tr>
<tr class="odd">
<td></td>
<td>EndOfTransaction</td>
<td>The end of transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>ItemDiscount</td>
<td>The item discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>ItemNotOnFile</td>
<td>The item not on file.</td>
</tr>
<tr class="even">
<td></td>
<td>LineItemTaxChange</td>
<td>The line item tax change.</td>
</tr>
<tr class="odd">
<td></td>
<td>Markup</td>
<td>The markup.</td>
</tr>
<tr class="even">
<td></td>
<td>NegativeAdjustment</td>
<td>The negative adjustment.</td>
</tr>
<tr class="odd">
<td></td>
<td>NfcEContingencyModeEnabled</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>NfcEVoided</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>OpenDrawer</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>OverridePrice</td>
<td>The override price.</td>
</tr>
<tr class="odd">
<td></td>
<td>ReturnItem</td>
<td>The return item.</td>
</tr>
<tr class="even">
<td></td>
<td>ReturnTransaction</td>
<td>The return transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>SerialNumber</td>
<td>The serial number.</td>
</tr>
<tr class="even">
<td></td>
<td>StartOfTransaction</td>
<td>The start of transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>TenderDeclaration</td>
<td>The tender declaration.</td>
</tr>
<tr class="even">
<td></td>
<td>TotalDiscount</td>
<td>The total discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>TransactionTaxChange</td>
<td>The transaction tax change.</td>
</tr>
<tr class="even">
<td></td>
<td>VoidItem</td>
<td>The void item.</td>
</tr>
<tr class="odd">
<td></td>
<td>VoidPayment</td>
<td>The void payment.</td>
</tr>
<tr class="even">
<td></td>
<td>VoidTransaction</td>
<td>The void transaction.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

