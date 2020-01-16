---
title: ProductVariant.DistinctProductVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DistinctProductVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.DistinctProductVariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.distinctproductvariantid(v=AX.60)
ms:contentKeyID: 62204408
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.DistinctProductVariantId
dev_langs:
- CSharp
- C++
- VB
---

# DistinctProductVariantId Property

Gets or sets the distinct product variant identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<KeyAttribute> _
<ColumnAttribute("DISTINCTPRODUCTVARIANT")> _
<RequiredAttribute> _
Public Property DistinctProductVariantId As Long
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As Long

value = instance.DistinctProductVariantId

instance.DistinctProductVariantId = value
```

``` csharp
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute("DISTINCTPRODUCTVARIANT")]
[RequiredAttribute]
public long DistinctProductVariantId { get; set; }
```

``` c++
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute(L"DISTINCTPRODUCTVARIANT")]
[RequiredAttribute]
public:
property long long DistinctProductVariantId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## Remarks

FK into AX2012 EcoResProduct tables. Identifies unique global variant.

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

