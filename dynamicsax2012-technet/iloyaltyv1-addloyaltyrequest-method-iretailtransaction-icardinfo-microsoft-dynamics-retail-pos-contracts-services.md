---
title: ILoyaltyV1.AddLoyaltyRequest Method (IRetailTransaction, ICardInfo) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLoyaltyRequest Method (IRetailTransaction, ICardInfo)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.AddLoyaltyRequest(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv1.addloyaltyrequest(v=AX.60)
ms:contentKeyID: 47343899
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddLoyaltyRequest Method (IRetailTransaction, ICardInfo)

Prompts the user whether to overwrite the existing loyalty item or cancel the operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AddLoyaltyRequest ( _
    retailTransaction As IRetailTransaction, _
    cardInfo As ICardInfo _
) As Boolean
'Usage
Dim instance As ILoyaltyV1
Dim retailTransaction As IRetailTransaction
Dim cardInfo As ICardInfo
Dim returnValue As Boolean

returnValue = instance.AddLoyaltyRequest(retailTransaction, _
    cardInfo)
```

``` csharp
bool AddLoyaltyRequest(
    IRetailTransaction retailTransaction,
    ICardInfo cardInfo
)
```

``` c++
bool AddLoyaltyRequest(
    IRetailTransaction^ retailTransaction, 
    ICardInfo^ cardInfo
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if add or update loyalty item to transaction is successful; otherwise, false.  

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
<td><p>Throws exception if retailTransaction is null.</p>
<p>-or-</p>
<p>Throws exception if cardInfo is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ILoyaltyV1 Interface](iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[AddLoyaltyRequest Overload](iloyaltyv1-addloyaltyrequest-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

