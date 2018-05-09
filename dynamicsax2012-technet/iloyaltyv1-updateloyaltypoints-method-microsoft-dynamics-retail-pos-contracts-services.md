---
title: ILoyaltyV1.UpdateLoyaltyPoints Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: UpdateLoyaltyPoints Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.UpdateLoyaltyPoints(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv1.updateloyaltypoints(v=AX.60)
ms:contentKeyID: 47344279
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.UpdateLoyaltyPoints
dev_langs:
- CSharp
- C++
- VB
---

# UpdateLoyaltyPoints Method

Called to update points in HQ when concluding a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub UpdateLoyaltyPoints ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ILoyaltyV1
Dim retailTransaction As IRetailTransaction

instance.UpdateLoyaltyPoints(retailTransaction)
```

``` csharp
void UpdateLoyaltyPoints(
    IRetailTransaction retailTransaction
)
```

``` c++
void UpdateLoyaltyPoints(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

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
<td><a href="https://technet.microsoft.com/en-us/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Throws exception if retailTransaction is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ILoyaltyV1 Interface](iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

