---
title: TenderDropAndDeclareType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderDropAndDeclareType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDropAndDeclareType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderdropanddeclaretype(v=AX.60)
ms:contentKeyID: 62210091
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDropAndDeclareType.BankDrop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDropAndDeclareType.SafeDrop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDropAndDeclareType.TenderDeclaration
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDropAndDeclareType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDropAndDeclareType
dev_langs:
- CSharp
- C++
- VB
---

# TenderDropAndDeclareType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the type of bank drop/ safe drop/ tender declaration daily operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration TenderDropAndDeclareType
'Usage
Dim instance As TenderDropAndDeclareType
```

``` csharp
[DataContractAttribute]
public enum TenderDropAndDeclareType
```

``` c++
[DataContractAttribute]
public enum class TenderDropAndDeclareType
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
<td>BankDrop</td>
<td>Bank drop helps to drop currencies into bank.</td>
</tr>
<tr class="odd">
<td></td>
<td>SafeDrop</td>
<td>Safedrop helps to drop currencies into safety locker.</td>
</tr>
<tr class="even">
<td></td>
<td>TenderDeclaration</td>
<td>Tender declaration is usually done when closing the shift.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

