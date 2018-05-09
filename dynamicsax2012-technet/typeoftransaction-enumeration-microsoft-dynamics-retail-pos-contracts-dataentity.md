---
title: TypeOfTransaction Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TypeOfTransaction Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.typeoftransaction(v=AX.60)
ms:contentKeyID: 49834832
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.IncomeExpense
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.PrintZ
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.FloatEntry
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.RemoveTender
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.PhysicalInventory
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.BankDrop
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.CustomerOrder
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.OpenDrawer
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.BlindCloseShift
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.StartingAmount
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.SafeDrop
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.EndOfDay
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.PrintX
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.SalesOrder
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.Sales
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.LogOff
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.Internal
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.SuspendShift
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.EndOfShift
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.Payment
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.NegativeAdjustment
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.TenderDeclaration
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.ChangeTender
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.SalesInvoice
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.LogOn
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.CloseShift
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.None
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TypeOfTransaction.PendingSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# TypeOfTransaction Enumeration

typeOfTransaction = TypeOfTransaction.LogOn;

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration TypeOfTransaction
'Usage
Dim instance As TypeOfTransaction
```

``` csharp
public enum TypeOfTransaction
```

``` c++
public enum class TypeOfTransaction
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
<td></td>
</tr>
<tr class="even">
<td></td>
<td>LogOff</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>LogOn</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>Sales</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>Payment</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>RemoveTender</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>FloatEntry</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>ChangeTender</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>TenderDeclaration</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>Internal</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>OpenDrawer</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>NegativeAdjustment</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>PhysicalInventory</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>EndOfDay</td>
<td><strong>Obsolete.</strong></td>
</tr>
<tr class="odd">
<td></td>
<td>EndOfShift</td>
<td><strong>Obsolete.</strong></td>
</tr>
<tr class="even">
<td></td>
<td>SalesOrder</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>SalesInvoice</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>BankDrop</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>SafeDrop</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>IncomeExpense</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>CustomerOrder</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>StartingAmount</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>SuspendShift</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>BlindCloseShift</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>CloseShift</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>PrintX</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>PrintZ</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>PendingSalesOrder</td>
<td></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

