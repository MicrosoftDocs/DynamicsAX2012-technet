---
title: CardEntryTypes Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CardEntryTypes Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardEntryTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.cardentrytypes(v=AX.60)
ms:contentKeyID: 47344502
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardEntryTypes
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardEntryTypes.CHIP_ENTRY
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardEntryTypes.MAGNETIC_STRIPE_READ
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardEntryTypes.MANUALLY_ENTERED
dev_langs:
- CSharp
- C++
- VB
---

# CardEntryTypes Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardEntryTypes interface specifies whether the card has been read with a stripe card reader or has been manually entered.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CardEntryTypes
'Usage
Dim instance As CardEntryTypes
```

``` csharp
public enum CardEntryTypes
```

``` c++
public enum class CardEntryTypes
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
<td>MAGNETIC_STRIPE_READ</td>
<td>Specifies the MAGNETIC_STRIPE_READ card entry type.</td>
</tr>
<tr class="even">
<td></td>
<td>MANUALLY_ENTERED</td>
<td>Specifies the MANUALLY_ENTERED card entry type.</td>
</tr>
<tr class="odd">
<td></td>
<td>CHIP_ENTRY</td>
<td>Specifies the CHIP_ENTRY card entry type.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

