---
title: IItemV1.MinAverageSettle Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: MinAverageSettle Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.MinAverageSettle
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.minaveragesettle(v=AX.60)
ms:contentKeyID: 49823521
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.MinAverageSettle
dev_langs:
- CSharp
- C++
- VB
---

# MinAverageSettle Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the min average settle.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MinAverageSettle As Decimal
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Decimal

value = instance.MinAverageSettle

instance.MinAverageSettle = value
```

``` csharp
decimal MinAverageSettle { get; set; }
```

``` c++
property Decimal MinAverageSettle {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The min average settle.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

