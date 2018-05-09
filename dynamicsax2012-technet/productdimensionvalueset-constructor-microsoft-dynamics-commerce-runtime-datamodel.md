---
title: ProductDimensionValueSet Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductDimensionValueSet Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueSet.#ctor(System.String,System.Collections.Generic.ICollection{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensionvalueset.productdimensionvalueset(v=AX.60)
ms:contentKeyID: 62212200
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueSet.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ProductDimensionValueSet Constructor

Initializes a new instance of the [ProductDimensionValueSet](productdimensionvalueset-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    dimensionValue As String, _
    variantIdSet As ICollection(Of Long) _
)
'Usage
Dim dimensionValue As String
Dim variantIdSet As ICollection(Of Long)

Dim instance As New ProductDimensionValueSet(dimensionValue, _
    variantIdSet)
```

``` csharp
public ProductDimensionValueSet(
    string dimensionValue,
    ICollection<long> variantIdSet
)
```

``` c++
public:
ProductDimensionValueSet(
    String^ dimensionValue, 
    ICollection<long long>^ variantIdSet
)
```

#### Parameters

  - dimensionValue  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantIdSet  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ProductDimensionValueSet Class](productdimensionvalueset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

