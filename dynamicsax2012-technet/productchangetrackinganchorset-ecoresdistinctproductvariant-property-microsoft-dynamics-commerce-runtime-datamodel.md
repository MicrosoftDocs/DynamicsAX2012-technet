---
title: ProductChangeTrackingAnchorSet.EcoResDistinctProductVariant Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResDistinctProductVariant Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResDistinctProductVariant
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresdistinctproductvariant(v=AX.60)
ms:contentKeyID: 62205120
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResDistinctProductVariant
dev_langs:
- CSharp
- C++
- VB
---

# EcoResDistinctProductVariant Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ECORESDISTINCTPRODUCTVARIANT")> _
Public Property EcoResDistinctProductVariant As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResDistinctProductVariant

instance.EcoResDistinctProductVariant = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ECORESDISTINCTPRODUCTVARIANT")]
public long EcoResDistinctProductVariant { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ECORESDISTINCTPRODUCTVARIANT")]
public:
property long long EcoResDistinctProductVariant {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

