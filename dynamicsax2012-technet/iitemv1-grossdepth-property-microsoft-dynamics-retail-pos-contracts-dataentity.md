---
title: IItemV1.GrossDepth Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: GrossDepth Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.GrossDepth
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.grossdepth(v=AX.60)
ms:contentKeyID: 49841406
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.GrossDepth
dev_langs:
- CSharp
- C++
- VB
---

# GrossDepth Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the gross depth.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property GrossDepth As Decimal
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Decimal

value = instance.GrossDepth

instance.GrossDepth = value
```

``` csharp
decimal GrossDepth { get; set; }
```

``` c++
property Decimal GrossDepth {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The gross depth.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

