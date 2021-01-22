---
title: CashGuardReturn Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CashGuardReturn Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.cashguardreturn(v=AX.60)
ms:contentKeyID: 47344324
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_CLOSED
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_SENDFAILED
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_WARNING
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_OK
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_BUSY
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_INPUT_PARAM_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_PAYOUT_LIMIT
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_PAYCLEAR_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_PORT_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_PAYOUT_REST
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn.CG_STATUS_TIMEOUT
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn
dev_langs:
- CSharp
- C++
- VB
---

# CashGuardReturn Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardReturn interface is the cash guard return class.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CashGuardReturn
'Usage
Dim instance As CashGuardReturn
```

``` csharp
public enum CashGuardReturn
```

``` c++
public enum class CashGuardReturn
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
<td>Indicates that the command was successfully executed.</td>
</tr>
<tr class="even">
<td></td>
<td>CG_STATUS_BUSY</td>
<td>Indicates that the cash changer was busy so the command couldn’t be sent to it.</td>
</tr>
<tr class="odd">
<td></td>
<td>CG_STATUS_ERROR</td>
<td>Indicates that an unspecified error occurred.</td>
</tr>
<tr class="even">
<td></td>
<td>CG_STATUS_WARNING</td>
<td>Indicates that the request could not be performed.</td>
</tr>
<tr class="odd">
<td></td>
<td>CG_STATUS_INPUT_PARAM_ERROR</td>
<td>Indicates that an input parameter is incorrect.</td>
</tr>
<tr class="even">
<td></td>
<td>CG_STATUS_CLOSED</td>
<td>Indicates that the cash changer was closed so the command couldn’t be sent to it.</td>
</tr>
<tr class="odd">
<td></td>
<td>CG_STATUS_TIMEOUT</td>
<td>Indicates that a time out occurred during a request.</td>
</tr>
<tr class="even">
<td></td>
<td>CG_STATUS_SENDFAILED</td>
<td>Indicates that a communication send error has occurred.</td>
</tr>
<tr class="odd">
<td></td>
<td>CG_STATUS_PAYOUT_REST</td>
<td>Indicates that payout is not possible because of a lack of suitable denominations.</td>
</tr>
<tr class="even">
<td></td>
<td>CG_STATUS_PORT_ERROR</td>
<td>Indicates that a communication receive error has occurred.</td>
</tr>
<tr class="odd">
<td></td>
<td>CG_STATUS_PAYCLEAR_ERROR</td>
<td>Indicates that the amount to deposit is too large.</td>
</tr>
<tr class="even">
<td></td>
<td>CG_STATUS_PAYOUT_LIMIT</td>
<td>Indicates that the payout is refused because it would result in too large of an amount being paid out during the last time period.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

