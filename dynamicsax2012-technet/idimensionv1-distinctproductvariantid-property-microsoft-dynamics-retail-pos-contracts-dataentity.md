---
title: IDimensionV1.DistinctProductVariantId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DistinctProductVariantId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDimensionV1.DistinctProductVariantId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.idimensionv1.distinctproductvariantid(v=AX.60)
ms:contentKeyID: 49856238
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDimensionV1.DistinctProductVariantId
dev_langs:
- CSharp
- C++
- VB
---

# DistinctProductVariantId Property

Rec Id in the EcoResDistinctProductVariant table for this particular combination

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DistinctProductVariantId As Long
    Get
    Set
'Usage
Dim instance As IDimensionV1
Dim value As Long

value = instance.DistinctProductVariantId

instance.DistinctProductVariantId = value
```

``` csharp
long DistinctProductVariantId { get; set; }
```

``` c++
property long long DistinctProductVariantId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[IDimensionV1 Interface](idimensionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

