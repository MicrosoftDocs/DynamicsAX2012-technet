---
title: CashGuardStaus Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CashGuardStaus Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardStaus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.cashguardstaus(v=AX.60)
ms:contentKeyID: 47344517
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardStaus
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardStaus.CG_STATUS_BUSY
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardStaus.CG_STATUS_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardStaus.CG_STATUS_OK
dev_langs:
- CSharp
- C++
- VB
---

# CashGuardStaus Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardStaus interface changes the cash status.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CashGuardStaus
'Usage
Dim instance As CashGuardStaus
```

``` csharp
public enum CashGuardStaus
```

``` c++
public enum class CashGuardStaus
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
<td>CG_STATUS_OK</td>
<td>Indicates that no errors have occurred.</td>
</tr>
<tr class="even">
<td></td>
<td>CG_STATUS_BUSY</td>
<td>Indicates that the cash changer is performing some task.</td>
</tr>
<tr class="odd">
<td></td>
<td>CG_STATUS_ERROR</td>
<td>Indicates that a CG_STATUS_ERROR error has occurred.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

