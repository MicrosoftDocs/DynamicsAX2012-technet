---
title: ILoyaltyV4.AddLoyaltyRequest Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLoyaltyRequest Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.AddLoyaltyRequest(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv4.addloyaltyrequest(v=AX.60)
ms:contentKeyID: 62204694
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.AddLoyaltyRequest
dev_langs:
- CSharp
- C++
- VB
---

# AddLoyaltyRequest Method

Adds loyalty request.

If a new customer is selected, old loyalty is removed.

If there is already a different loyalty associated with the transaction, user is prometed to chose.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AddLoyaltyRequest ( _
    retailTransaction As IRetailTransaction _
) As Boolean
'Usage
Dim instance As ILoyaltyV4
Dim retailTransaction As IRetailTransaction
Dim returnValue As Boolean

returnValue = instance.AddLoyaltyRequest(retailTransaction)
```

``` csharp
bool AddLoyaltyRequest(
    IRetailTransaction retailTransaction
)
```

``` c++
bool AddLoyaltyRequest(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if loyalty was added to the transaction.  

## See Also

#### Reference

[ILoyaltyV4 Interface](iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

