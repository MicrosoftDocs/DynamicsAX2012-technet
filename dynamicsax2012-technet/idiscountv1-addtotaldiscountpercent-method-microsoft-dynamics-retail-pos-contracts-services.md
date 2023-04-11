---
title: IDiscountV1.AddTotalDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddTotalDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddTotalDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.addtotaldiscountpercent(v=AX.60)
ms:contentKeyID: 47343934
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddTotalDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# AddTotalDiscountPercent Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Applies the provided percentage value as a discount to the total transaction balance.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddTotalDiscountPercent ( _
    retailTransaction As IRetailTransaction, _
    percentValue As Decimal _
)
'Usage
Dim instance As IDiscountV1
Dim retailTransaction As IRetailTransaction
Dim percentValue As Decimal

instance.AddTotalDiscountPercent(retailTransaction, _
    percentValue)
```

``` csharp
void AddTotalDiscountPercent(
    IRetailTransaction retailTransaction,
    decimal percentValue
)
```

``` c++
void AddTotalDiscountPercent(
    IRetailTransaction^ retailTransaction, 
    Decimal percentValue
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - percentValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## Remarks

This method is invoked by the total discount percentage operation.

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

