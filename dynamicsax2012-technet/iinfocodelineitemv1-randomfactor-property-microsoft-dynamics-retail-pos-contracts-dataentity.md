---
title: IInfoCodeLineItemV1.RandomFactor Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RandomFactor Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.RandomFactor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.randomfactor(v=AX.60)
ms:contentKeyID: 49832052
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.RandomFactor
dev_langs:
- CSharp
- C++
- VB
---

# RandomFactor Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The random factor;

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RandomFactor As Decimal
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As Decimal

value = instance.RandomFactor

instance.RandomFactor = value
```

``` csharp
decimal RandomFactor { get; set; }
```

``` c++
property Decimal RandomFactor {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

