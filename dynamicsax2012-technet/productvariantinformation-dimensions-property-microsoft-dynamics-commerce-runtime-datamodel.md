---
title: ProductVariantInformation.Dimensions Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Dimensions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.Dimensions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantinformation.dimensions(v=AX.60)
ms:contentKeyID: 62201865
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.Dimensions
dev_langs:
- CSharp
- C++
- VB
---

# Dimensions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the dimension properties of this product as a flat list, complete with values and variant ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Dimensions As ICollection(Of ProductDimensionSet)
    Get
    Friend Set
'Usage
Dim instance As ProductVariantInformation
Dim value As ICollection(Of ProductDimensionSet)

value = instance.Dimensions
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductDimensionSet> Dimensions { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductDimensionSet^>^ Dimensions {
    ICollection<ProductDimensionSet^>^ get ();
    internal: void set (ICollection<ProductDimensionSet^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductDimensionSet](productdimensionset-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariantInformation Class](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

