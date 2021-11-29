---
title: ProductChangeTrackingAnchorSet.EcoResProductVariantDimensionValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResProductVariantDimensionValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResProductVariantDimensionValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresproductvariantdimensionvalue(v=AX.60)
ms:contentKeyID: 62212955
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResProductVariantDimensionValue
dev_langs:
- CSharp
- C++
- VB
---

# EcoResProductVariantDimensionValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ECORESPRODUCTVARIANTDIMENSIONVALUE")> _
<DataMemberAttribute> _
Public Property EcoResProductVariantDimensionValue As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResProductVariantDimensionValue

instance.EcoResProductVariantDimensionValue = value
```

``` csharp
[ColumnAttribute("ECORESPRODUCTVARIANTDIMENSIONVALUE")]
[DataMemberAttribute]
public long EcoResProductVariantDimensionValue { get; set; }
```

``` c++
[ColumnAttribute(L"ECORESPRODUCTVARIANTDIMENSIONVALUE")]
[DataMemberAttribute]
public:
property long long EcoResProductVariantDimensionValue {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

