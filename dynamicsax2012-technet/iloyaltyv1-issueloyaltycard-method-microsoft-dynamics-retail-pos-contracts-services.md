---
title: ILoyaltyV1.IssueLoyaltyCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IssueLoyaltyCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.IssueLoyaltyCard(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv1.issueloyaltycard(v=AX.60)
ms:contentKeyID: 62202223
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.IssueLoyaltyCard
dev_langs:
- CSharp
- C++
- VB
---

# IssueLoyaltyCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Isses loyalty card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IssueLoyaltyCard ( _
    retailTransaction As IRetailTransaction _
) As Boolean
'Usage
Dim instance As ILoyaltyV1
Dim retailTransaction As IRetailTransaction
Dim returnValue As Boolean

returnValue = instance.IssueLoyaltyCard(retailTransaction)
```

``` csharp
bool IssueLoyaltyCard(
    IRetailTransaction retailTransaction
)
```

``` c++
bool IssueLoyaltyCard(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if loyalty card is issued.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Throws exception if retailTransaction is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ILoyaltyV1 Interface](iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

