---
title: IDiscountV2.CalculateSimpleDiscount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateSimpleDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV2.CalculateSimpleDiscount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv2.calculatesimplediscount(v=AX.60)
ms:contentKeyID: 62204989
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV2.CalculateSimpleDiscount
dev_langs:
- CSharp
- C++
- VB
---

# CalculateSimpleDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calcalute simple discount, like discount offer. This is to delay computation heavy discount calculation until all items have been scanned.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateSimpleDiscount ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As IDiscountV2
Dim retailTransaction As IRetailTransaction

instance.CalculateSimpleDiscount(retailTransaction)
```

``` csharp
void CalculateSimpleDiscount(
    IRetailTransaction retailTransaction
)
```

``` c++
void CalculateSimpleDiscount(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IDiscountV2 Interface](idiscountv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

