---
title: IUnitQtyConversionV1.Convert Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Convert Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IUnitQtyConversionV1.Convert(System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iunitqtyconversionv1.convert(v=AX.60)
ms:contentKeyID: 49836745
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IUnitQtyConversionV1.Convert
dev_langs:
- CSharp
- C++
- VB
---

# Convert Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Uses conversion's previously set factor, numerator, and direction to convert a given quantity

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Convert ( _
    fromQty As Decimal _
) As Decimal
'Usage
Dim instance As IUnitQtyConversionV1
Dim fromQty As Decimal
Dim returnValue As Decimal

returnValue = instance.Convert(fromQty)
```

``` csharp
decimal Convert(
    decimal fromQty
)
```

``` c++
Decimal Convert(
    Decimal fromQty
)
```

#### Parameters

  - fromQty  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Quantity converted using factor, numerator, denominator, inneroffset, outeroffset and direction  

## See Also

#### Reference

[IUnitQtyConversionV1 Interface](iunitqtyconversionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

