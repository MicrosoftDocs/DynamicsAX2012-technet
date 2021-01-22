---
title: CashGuardWarningType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CashGuardWarningType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardWarningType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.cashguardwarningtype(v=AX.60)
ms:contentKeyID: 47344348
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardWarningType
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardWarningType.LEVEL_BLOCK
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardWarningType.LEVEL_EMPTY
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardWarningType.LEVEL_HIGH
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardWarningType.LEVEL_LOW
dev_langs:
- CSharp
- C++
- VB
---

# CashGuardWarningType Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardWarningType interface is unsupported.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CashGuardWarningType
'Usage
Dim instance As CashGuardWarningType
```

``` csharp
public enum CashGuardWarningType
```

``` c++
public enum class CashGuardWarningType
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
<td>LEVEL_EMPTY</td>
<td>Indicates that there are no coins or notes left of this denomination.</td>
</tr>
<tr class="even">
<td></td>
<td>LEVEL_LOW</td>
<td>Indicates that the level is less than the low warning level configured from the back office.</td>
</tr>
<tr class="odd">
<td></td>
<td>LEVEL_HIGH</td>
<td>Indicates that the level is grater than the high warning level configured from the back office.</td>
</tr>
<tr class="even">
<td></td>
<td>LEVEL_BLOCK</td>
<td>Indicates that the denomination is completely full and no more coins or notes of that denomination can be inserted.</td>
</tr>
</tbody>
</table>


## Remarks

This interface should not be used.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

