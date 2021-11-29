---
title: IUnitQtyConversionV1.Factor Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Factor Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IUnitQtyConversionV1.Factor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iunitqtyconversionv1.factor(v=AX.60)
ms:contentKeyID: 49841363
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IUnitQtyConversionV1.Factor
dev_langs:
- CSharp
- C++
- VB
---

# Factor Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Multiplicative part of conversion. Direction decides multiplying or dividing.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Factor As Decimal
    Get
'Usage
Dim instance As IUnitQtyConversionV1
Dim value As Decimal

value = instance.Factor
```

``` csharp
decimal Factor { get; }
```

``` c++
property Decimal Factor {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IUnitQtyConversionV1 Interface](iunitqtyconversionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

