---
title: IItemV1.Density Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Density Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.Density
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.density(v=AX.60)
ms:contentKeyID: 49846384
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.Density
dev_langs:
- CSharp
- C++
- VB
---

# Density Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the density.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Density As Decimal
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Decimal

value = instance.Density

instance.Density = value
```

``` csharp
decimal Density { get; set; }
```

``` c++
property Decimal Density {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The density.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

