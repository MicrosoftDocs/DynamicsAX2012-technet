---
title: IDiscountV1.CalculateDiscount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.CalculateDiscount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.calculatediscount(v=AX.60)
ms:contentKeyID: 47344395
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.CalculateDiscount
dev_langs:
- CSharp
- C++
- VB
---

# CalculateDiscount Method

Calculates the discounts for all sales lines for the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateDiscount ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As IDiscountV1
Dim retailTransaction As IRetailTransaction

instance.CalculateDiscount(retailTransaction)
```

``` csharp
void CalculateDiscount(
    IRetailTransaction retailTransaction
)
```

``` c++
void CalculateDiscount(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

