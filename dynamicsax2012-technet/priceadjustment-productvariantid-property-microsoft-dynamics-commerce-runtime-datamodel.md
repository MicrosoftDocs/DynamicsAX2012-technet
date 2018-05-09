---
title: PriceAdjustment.ProductVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ProductVariantId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.productvariantid(v=AX.60)
ms:contentKeyID: 49835825
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ProductVariantId
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariantId Property

Gets the identifier of the distinct product variant with which this price adjustment is associated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISTINCTPRODUCTVARIANT")> _
Public Property ProductVariantId As Long
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As Long

value = instance.ProductVariantId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISTINCTPRODUCTVARIANT")]
public long ProductVariantId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISTINCTPRODUCTVARIANT")]
public:
property long long ProductVariantId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

