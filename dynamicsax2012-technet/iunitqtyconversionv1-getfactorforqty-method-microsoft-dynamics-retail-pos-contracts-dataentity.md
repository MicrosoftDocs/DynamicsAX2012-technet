---
title: IUnitQtyConversionV1.GetFactorForQty Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: GetFactorForQty Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IUnitQtyConversionV1.GetFactorForQty(System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iunitqtyconversionv1.getfactorforqty(v=AX.60)
ms:contentKeyID: 49854044
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IUnitQtyConversionV1.GetFactorForQty
dev_langs:
- CSharp
- C++
- VB
---

# GetFactorForQty Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

With Markup, the overall "factor" changes depending on quantity converted.

For easier use with code assuming a simple factor, this returns that "factor" for a given quantity

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetFactorForQty ( _
    qty As Decimal _
) As Decimal
'Usage
Dim instance As IUnitQtyConversionV1
Dim qty As Decimal
Dim returnValue As Decimal

returnValue = instance.GetFactorForQty(qty)
```

``` csharp
decimal GetFactorForQty(
    decimal qty
)
```

``` c++
Decimal GetFactorForQty(
    Decimal qty
)
```

#### Parameters

  - qty  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Overall factor for given quantity  

## See Also

#### Reference

[IUnitQtyConversionV1 Interface](iunitqtyconversionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

