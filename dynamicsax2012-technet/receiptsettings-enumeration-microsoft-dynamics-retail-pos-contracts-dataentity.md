---
title: ReceiptSettings Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ReceiptSettings Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ReceiptSettings
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.receiptsettings(v=AX.60)
ms:contentKeyID: 47128080
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ReceiptSettings
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ReceiptSettings.POS
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ReceiptSettings.BOTH
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ReceiptSettings.EMAIL
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptSettings Enumeration

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration ReceiptSettings
'Usage
Dim instance As ReceiptSettings
```

``` csharp
public enum ReceiptSettings
```

``` c++
public enum class ReceiptSettings
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
<td>POS</td>
<td>The receipt should be printed on the POS.</td>
</tr>
<tr class="even">
<td></td>
<td>EMAIL</td>
<td>The receipt should be sent as an email to the customer.</td>
</tr>
<tr class="odd">
<td></td>
<td>BOTH</td>
<td>The receipt should be printed on the POS and sent as an email to the customer.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

