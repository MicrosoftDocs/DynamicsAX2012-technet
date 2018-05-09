---
title: ILoyaltyV4.TryToAddLoyaltyRequest Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TryToAddLoyaltyRequest Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.TryToAddLoyaltyRequest(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv4.trytoaddloyaltyrequest(v=AX.60)
ms:contentKeyID: 62204372
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.TryToAddLoyaltyRequest
dev_langs:
- CSharp
- C++
- VB
---

# TryToAddLoyaltyRequest Method

Adds loyalty to the transaction, if any.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function TryToAddLoyaltyRequest ( _
    retailTransaction As IRetailTransaction _
) As Boolean
'Usage
Dim instance As ILoyaltyV4
Dim retailTransaction As IRetailTransaction
Dim returnValue As Boolean

returnValue = instance.TryToAddLoyaltyRequest(retailTransaction)
```

``` csharp
bool TryToAddLoyaltyRequest(
    IRetailTransaction retailTransaction
)
```

``` c++
bool TryToAddLoyaltyRequest(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if loyalty was added to the transaction.  

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

[ILoyaltyV4 Interface](iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

