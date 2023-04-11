---
title: ILoyaltyV4.GetLoyaltyBalance Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetLoyaltyBalance Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.GetLoyaltyBalance(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv4.getloyaltybalance(v=AX.60)
ms:contentKeyID: 62205196
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.GetLoyaltyBalance
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyBalance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets loyalty card balance

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetLoyaltyBalance ( _
    retailTransaction As IRetailTransaction _
) As Decimal
'Usage
Dim instance As ILoyaltyV4
Dim retailTransaction As IRetailTransaction
Dim returnValue As Decimal

returnValue = instance.GetLoyaltyBalance(retailTransaction)
```

``` csharp
decimal GetLoyaltyBalance(
    IRetailTransaction retailTransaction
)
```

``` c++
Decimal GetLoyaltyBalance(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Number of loyalty points that can be used for specified loyalty card or customer  

## See Also

#### Reference

[ILoyaltyV4 Interface](iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

