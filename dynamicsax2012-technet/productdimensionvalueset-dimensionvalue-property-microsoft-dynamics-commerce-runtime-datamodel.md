---
title: ProductDimensionValueSet.DimensionValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DimensionValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueSet.DimensionValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensionvalueset.dimensionvalue(v=AX.60)
ms:contentKeyID: 62204342
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueSet.DimensionValue
dev_langs:
- CSharp
- C++
- VB
---

# DimensionValue Property

Gets the value of this dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property DimensionValue As String
    Get
    Friend Set
'Usage
Dim instance As ProductDimensionValueSet
Dim value As String

value = instance.DimensionValue
```

``` csharp
public string DimensionValue { get; internal set; }
```

``` c++
public:
property String^ DimensionValue {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductDimensionValueSet Class](productdimensionvalueset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

