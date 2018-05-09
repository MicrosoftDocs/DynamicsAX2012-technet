---
title: InfoCodeInputType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InfoCodeInputType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.infocodeinputtype(v=AX.60)
ms:contentKeyID: 47128487
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.SubCodeButtons
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.General
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.Text
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.Operator
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.Date
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.SubCodeList
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.Item
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.AgeLimit
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.ApplyToEntry
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.CreateDataEntry
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.Customer
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType.Numeric
dev_langs:
- CSharp
- C++
- VB
---

# InfoCodeInputType Enumeration

Specifies the Infocode input type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration InfoCodeInputType
'Usage
Dim instance As InfoCodeInputType
```

``` csharp
public enum InfoCodeInputType
```

``` c++
public enum class InfoCodeInputType
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
<td>General</td>
<td>General = 0</td>
</tr>
<tr class="even">
<td></td>
<td>SubCodeList</td>
<td>The input is a list of subcodes presented as a list.</td>
</tr>
<tr class="odd">
<td></td>
<td>Date</td>
<td>The input is a date.</td>
</tr>
<tr class="even">
<td></td>
<td>Numeric</td>
<td>The input is numeric.</td>
</tr>
<tr class="odd">
<td></td>
<td>Item</td>
<td>The input is an item.</td>
</tr>
<tr class="even">
<td></td>
<td>Customer</td>
<td>The input is a customer.</td>
</tr>
<tr class="odd">
<td></td>
<td>Operator</td>
<td>The input is a worker.</td>
</tr>
<tr class="even">
<td></td>
<td>CreateDataEntry</td>
<td>Thiswill not be implemented in Retail POS</td>
</tr>
<tr class="odd">
<td></td>
<td>ApplyToEntry</td>
<td>This will not be implemented in Retail POS</td>
</tr>
<tr class="even">
<td></td>
<td>Text</td>
<td>The input is text.</td>
</tr>
<tr class="odd">
<td></td>
<td>SubCodeButtons</td>
<td>The input is a list of subcodes presented as buttons.</td>
</tr>
<tr class="even">
<td></td>
<td>AgeLimit</td>
<td>The input is the minimum age that the customer must be to make a purchase.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

