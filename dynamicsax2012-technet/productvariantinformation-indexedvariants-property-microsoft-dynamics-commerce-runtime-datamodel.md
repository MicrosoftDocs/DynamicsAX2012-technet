---
title: ProductVariantInformation.IndexedVariants Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedVariants Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.IndexedVariants
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantinformation.indexedvariants(v=AX.60)
ms:contentKeyID: 62204741
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.IndexedVariants
dev_langs:
- CSharp
- C++
- VB
---

# IndexedVariants Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the properties of the variants of the master product, indexed by the variant id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedVariants As ProductVariantDictionary
    Get
    Friend Set
'Usage
Dim instance As ProductVariantInformation
Dim value As ProductVariantDictionary

value = instance.IndexedVariants
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductVariantDictionary IndexedVariants { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductVariantDictionary^ IndexedVariants {
    ProductVariantDictionary^ get ();
    internal: void set (ProductVariantDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantDictionary](productvariantdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductVariantDictionary](productvariantdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductVariantInformation Class](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

