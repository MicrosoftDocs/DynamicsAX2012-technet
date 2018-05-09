---
title: PinPadEntryStatus Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PinPadEntryStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.pinpadentrystatus(v=AX.60)
ms:contentKeyID: 47344103
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus.BadKey
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus.Cancel
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus.Error
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus.Success
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus.Timeout
dev_langs:
- CSharp
- C++
- VB
---

# PinPadEntryStatus Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus interface is the pin entry status type interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PinPadEntryStatus
'Usage
Dim instance As PinPadEntryStatus
```

``` csharp
public enum PinPadEntryStatus
```

``` c++
public enum class PinPadEntryStatus
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
<td>Success</td>
<td>Indicates a PIN entry has occurred.</td>
</tr>
<tr class="even">
<td></td>
<td>Cancel</td>
<td>Indicates the user hit the cancel button on the PIN Pad.</td>
</tr>
<tr class="odd">
<td></td>
<td>Timeout</td>
<td>Indicates a time-out condition occurred in the PIN Pad.</td>
</tr>
<tr class="even">
<td></td>
<td>Error</td>
<td>Indicates an error has occurred.</td>
</tr>
<tr class="odd">
<td></td>
<td>BadKey</td>
<td>BadKey</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

