---
title: CashChangerReturn Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CashChangerReturn Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.cashchangerreturn(v=AX.60)
ms:contentKeyID: 47344309
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_PAYOUT_LIMIT
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_PAYCLEAR_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_INPUT_PARAM_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_OK
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_PORT_ERROR
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_WARNING
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_TIMEOUT
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_CLOSED
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_PAYOUT_REST
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_SENDFAILED
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn.STATUS_BUSY
dev_langs:
- CSharp
- C++
- VB
---

# CashChangerReturn Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn interface is unsupported. Do not use.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CashChangerReturn
'Usage
Dim instance As CashChangerReturn
```

``` csharp
public enum CashChangerReturn
```

``` c++
public enum class CashChangerReturn
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
<td>STATUS_OK</td>
<td>Indicates that the command was successfully executed.</td>
</tr>
<tr class="even">
<td></td>
<td>STATUS_BUSY</td>
<td>Indicates that cash changer was busy so the command couldn’t be sent to it.</td>
</tr>
<tr class="odd">
<td></td>
<td>STATUS_ERROR</td>
<td>Indicates that an unspecified error occurred.</td>
</tr>
<tr class="even">
<td></td>
<td>STATUS_WARNING</td>
<td>The request could not be performed.</td>
</tr>
<tr class="odd">
<td></td>
<td>STATUS_INPUT_PARAM_ERROR</td>
<td>Indicates that some input parameter is incorrect.</td>
</tr>
<tr class="even">
<td></td>
<td>STATUS_CLOSED</td>
<td>Indicates that cash changer was closed so the command couldn’t be sent to it.</td>
</tr>
<tr class="odd">
<td></td>
<td>STATUS_TIMEOUT</td>
<td>Indicates that a time out occurred during a request.</td>
</tr>
<tr class="even">
<td></td>
<td>STATUS_SENDFAILED</td>
<td>Indicates that a communication send error has occurred.</td>
</tr>
<tr class="odd">
<td></td>
<td>STATUS_PAYOUT_REST</td>
<td>Indicates that payout not possible because of a lack of suitable denominations.</td>
</tr>
<tr class="even">
<td></td>
<td>STATUS_PORT_ERROR</td>
<td>Indicates that a communication receive error has occurred.</td>
</tr>
<tr class="odd">
<td></td>
<td>STATUS_PAYCLEAR_ERROR</td>
<td>Indicates that the amount to deposit is too large.</td>
</tr>
<tr class="even">
<td></td>
<td>STATUS_PAYOUT_LIMIT</td>
<td>Indicates that payout is refused because it would result in a too large of an amount being paid out during the last time period.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

