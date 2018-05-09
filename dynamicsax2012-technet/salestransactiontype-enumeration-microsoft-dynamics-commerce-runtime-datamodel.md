---
title: SalesTransactionType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTransactionType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiontype(v=AX.60)
ms:contentKeyID: 62208521
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType.Sales
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType.CustomerOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType.IncomeExpense
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType.PendingSalesOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType.CustomerAccountDeposit
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransactionType Enumeration

Represents the type of sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration SalesTransactionType
'Usage
Dim instance As SalesTransactionType
```

``` csharp
[DataContractAttribute]
public enum SalesTransactionType
```

``` c++
[DataContractAttribute]
public enum class SalesTransactionType
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
<td>No transaction type specified.</td>
</tr>
<tr class="even">
<td></td>
<td>Sales</td>
<td>Cash And Carry Transactions. This type includes both sales transactions and return transactions.</td>
</tr>
<tr class="odd">
<td></td>
<td>CustomerAccountDeposit</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>IncomeExpense</td>
<td>Income / Expense accounts maintains income / expense amounts other than sale.</td>
</tr>
<tr class="odd">
<td></td>
<td>CustomerOrder</td>
<td>A customer order (created through transaction service).</td>
</tr>
<tr class="even">
<td></td>
<td>PendingSalesOrder</td>
<td>Pending sales orders (created through P-jobs).</td>
</tr>
</tbody>
</table>


## Remarks

Values should be a subset of [TransactionType](transactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

