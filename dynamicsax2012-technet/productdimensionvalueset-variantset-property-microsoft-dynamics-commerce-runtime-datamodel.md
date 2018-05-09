---
title: ProductDimensionValueSet.VariantSet Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VariantSet Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueSet.VariantSet
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensionvalueset.variantset(v=AX.60)
ms:contentKeyID: 62206865
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueSet.VariantSet
dev_langs:
- CSharp
- C++
- VB
---

# VariantSet Property

Gets the set of variants of this product with the current value for this dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property VariantSet As ICollection(Of Long)
    Get
    Friend Set
'Usage
Dim instance As ProductDimensionValueSet
Dim value As ICollection(Of Long)

value = instance.VariantSet
```

``` csharp
public ICollection<long> VariantSet { get; internal set; }
```

``` c++
public:
property ICollection<long long>^ VariantSet {
    ICollection<long long>^ get ();
    internal: void set (ICollection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductDimensionValueSet Class](productdimensionvalueset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

