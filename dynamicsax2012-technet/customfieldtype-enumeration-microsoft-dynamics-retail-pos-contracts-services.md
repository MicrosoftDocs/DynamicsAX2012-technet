---
title: CustomFieldType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CustomFieldType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.customfieldtype(v=AX.60)
ms:contentKeyID: 47343855
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldType
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldType.ItemReceiptGrid
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldType.JournalReceipt
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldType.PaymentGrid
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldType.TotalsArea
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldType.CustomControl
dev_langs:
- CSharp
- C++
- VB
---

# CustomFieldType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.CustomFieldType interface is the location where a custom field is used.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CustomFieldType
'Usage
Dim instance As CustomFieldType
```

``` csharp
public enum CustomFieldType
```

``` c++
public enum class CustomFieldType
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
<td>ItemReceiptGrid</td>
<td>Specifies the item receipt grid in the main layout of POS.</td>
</tr>
<tr class="even">
<td></td>
<td>PaymentGrid</td>
<td>Specifies a payment grid in the main layout of POS.</td>
</tr>
<tr class="odd">
<td></td>
<td>TotalsArea</td>
<td>Specifies the totals area in the main layout of POS.</td>
</tr>
<tr class="even">
<td></td>
<td>JournalReceipt</td>
<td>Specifies on a printed receipt.</td>
</tr>
<tr class="odd">
<td></td>
<td>CustomControl</td>
<td>CustomControl = 4</td>
</tr>
</tbody>
</table>


## Remarks

Linked to AX:RetailTerminalCustomFieldType

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

