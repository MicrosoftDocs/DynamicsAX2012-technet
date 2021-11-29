---
title: ProductVariantInformation.IndexedDimensions Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedDimensions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.IndexedDimensions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantinformation.indexeddimensions(v=AX.60)
ms:contentKeyID: 62214971
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.IndexedDimensions
dev_langs:
- CSharp
- C++
- VB
---

# IndexedDimensions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the dimension properties of this product, grouped by value, along with the variant ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedDimensions As ProductDimensionDictionary
    Get
    Friend Set
'Usage
Dim instance As ProductVariantInformation
Dim value As ProductDimensionDictionary

value = instance.IndexedDimensions
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductDimensionDictionary IndexedDimensions { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductDimensionDictionary^ IndexedDimensions {
    ProductDimensionDictionary^ get ();
    internal: void set (ProductDimensionDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionDictionary](productdimensiondictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductDimensionDictionary](productdimensiondictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductVariantInformation Class](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

