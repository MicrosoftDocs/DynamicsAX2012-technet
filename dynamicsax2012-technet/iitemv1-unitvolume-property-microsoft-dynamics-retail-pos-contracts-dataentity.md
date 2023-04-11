---
title: IItemV1.UnitVolume Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: UnitVolume Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.UnitVolume
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.unitvolume(v=AX.60)
ms:contentKeyID: 49851027
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.UnitVolume
dev_langs:
- CSharp
- C++
- VB
---

# UnitVolume Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit volume.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property UnitVolume As Decimal
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Decimal

value = instance.UnitVolume

instance.UnitVolume = value
```

``` csharp
decimal UnitVolume { get; set; }
```

``` c++
property Decimal UnitVolume {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The unit volume.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

