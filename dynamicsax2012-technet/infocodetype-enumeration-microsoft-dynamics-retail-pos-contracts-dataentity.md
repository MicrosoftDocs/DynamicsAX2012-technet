---
title: InfoCodeType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InfoCodeType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.infocodetype(v=AX.60)
ms:contentKeyID: 47128274
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType.IncomeExpense
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType.Header
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType.Payment
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType.Sales
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType.Affiliation
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType.NoSale
dev_langs:
- CSharp
- C++
- VB
---

# InfoCodeType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Specifies the Infocode type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration InfoCodeType
'Usage
Dim instance As InfoCodeType
```

``` csharp
public enum InfoCodeType
```

``` c++
public enum class InfoCodeType
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
<td>Header</td>
<td>An Infocode on a transaction header.</td>
</tr>
<tr class="even">
<td></td>
<td>Sales</td>
<td>An Infocode on a sales line.</td>
</tr>
<tr class="odd">
<td></td>
<td>Payment</td>
<td>An Infocode on a payment line.</td>
</tr>
<tr class="even">
<td></td>
<td>IncomeExpense</td>
<td>An Infocode on an IncomeExpense transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>NoSale</td>
<td>No Sale = 4</td>
</tr>
<tr class="even">
<td></td>
<td>Affiliation</td>
<td>Affiliation</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

