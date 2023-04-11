---
title: TransactionType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactiontype(v=AX.60)
ms:contentKeyID: 62208981
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.ChangeTender
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.CloseShift
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.BankDrop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.LogOff
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.FloatEntry
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.ChangePassword
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.BlindCloseShift
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.PendingSalesOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.KitDisassembly
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.OpenDrawer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.LogOn
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.Payment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.CustomerOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.IncomeExpense
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.RemoveTender
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.ResetPassword
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.SalesInvoice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.SalesOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.Sales
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.TenderDeclaration
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.StartingAmount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.SafeDrop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.SuspendShift
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.PrintX
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType.PrintZ
dev_langs:
- CSharp
- C++
- VB
---

# TransactionType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the type of transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration TransactionType
'Usage
Dim instance As TransactionType
```

``` csharp
[DataContractAttribute]
public enum TransactionType
```

``` c++
[DataContractAttribute]
public enum class TransactionType
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
<td>LogOff</td>
<td>Login transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>LogOn</td>
<td>Logout transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>ResetPassword</td>
<td>Reset Password transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>ChangePassword</td>
<td>Change Password transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>Sales</td>
<td>Cash And Carry Transactions. This type includes both sales transactions and return transactions.</td>
</tr>
<tr class="odd">
<td></td>
<td>Payment</td>
<td>A payment transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>RemoveTender</td>
<td>Tender removal is used to transfer cash to different registry.</td>
</tr>
<tr class="odd">
<td></td>
<td>FloatEntry</td>
<td>Float Entry is used to transfer cash to different registry.</td>
</tr>
<tr class="even">
<td></td>
<td>ChangeTender</td>
<td>Change Tender.</td>
</tr>
<tr class="odd">
<td></td>
<td>TenderDeclaration</td>
<td>Tender declaration is usually done when closing the shift.</td>
</tr>
<tr class="even">
<td></td>
<td>OpenDrawer</td>
<td>Open drawer helps cashier to open drawer to maintain cash of multiple currencies.</td>
</tr>
<tr class="odd">
<td></td>
<td>SalesOrder</td>
<td>A sales order.</td>
</tr>
<tr class="even">
<td></td>
<td>SalesInvoice</td>
<td>A sales invoice.</td>
</tr>
<tr class="odd">
<td></td>
<td>BankDrop</td>
<td>Bank drop helps to drop currencies into bank.</td>
</tr>
<tr class="even">
<td></td>
<td>SafeDrop</td>
<td>Safedrop helps to drop currencies into safety locker.</td>
</tr>
<tr class="odd">
<td></td>
<td>IncomeExpense</td>
<td>Income / Expense accounts maintains income / expense amounts other than sale.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerOrder</td>
<td>A customer order (created through transaction service).</td>
</tr>
<tr class="odd">
<td></td>
<td>StartingAmount</td>
<td>Declare start amount helps to declare starting amount when the shift is open.</td>
</tr>
<tr class="even">
<td></td>
<td>SuspendShift</td>
<td>Suspend ShiftStaging Transactions.</td>
</tr>
<tr class="odd">
<td></td>
<td>BlindCloseShift</td>
<td>Blindly Close ShiftStaging Transactions.</td>
</tr>
<tr class="even">
<td></td>
<td>CloseShift</td>
<td>Close ShiftStaging Transactions.</td>
</tr>
<tr class="odd">
<td></td>
<td>PrintX</td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>PrintZ</td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td>PendingSalesOrder</td>
<td>Pending sales orders.</td>
</tr>
<tr class="even">
<td></td>
<td>KitDisassembly</td>
<td>Kit disassembly transaction.</td>
</tr>
</tbody>
</table>


## Remarks

In AX, this is represented as RetailTransactionType base enum.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

