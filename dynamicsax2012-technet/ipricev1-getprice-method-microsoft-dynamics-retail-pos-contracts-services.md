---
title: IPriceV1.GetPrice Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetPrice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV1.GetPrice(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipricev1.getprice(v=AX.60)
ms:contentKeyID: 47344359
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV1.GetPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetPrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called from the BusinessLogic and ItemSystem.cs classes.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetPrice ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As IPriceV1
Dim retailTransaction As IRetailTransaction

instance.GetPrice(retailTransaction)
```

``` csharp
void GetPrice(
    IRetailTransaction retailTransaction
)
```

``` c++
void GetPrice(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IPriceV1 Interface](ipricev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

