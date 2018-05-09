---
title: StatementMethod Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatementMethod Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.StatementMethod
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.statementmethod(v=AX.60)
ms:contentKeyID: 62205379
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StatementMethod.Total
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StatementMethod.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StatementMethod
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StatementMethod.Staff
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StatementMethod.PosTerminal
dev_langs:
- CSharp
- C++
- VB
---

# StatementMethod Enumeration

The statement methods enum.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration StatementMethod
'Usage
Dim instance As StatementMethod
```

``` csharp
[DataContractAttribute]
public enum StatementMethod
```

``` c++
[DataContractAttribute]
public enum class StatementMethod
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
<td>No statement method.</td>
</tr>
<tr class="even">
<td></td>
<td>Staff</td>
<td>Staff statement method.</td>
</tr>
<tr class="odd">
<td></td>
<td>PosTerminal</td>
<td>POS terminal statement method.</td>
</tr>
<tr class="even">
<td></td>
<td>Total</td>
<td>Total statement method.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailStatementMethod enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

