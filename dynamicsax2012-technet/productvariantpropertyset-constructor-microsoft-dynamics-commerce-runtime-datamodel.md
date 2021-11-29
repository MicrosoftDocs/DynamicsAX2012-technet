---
title: ProductVariantPropertySet Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantPropertySet Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertySet.#ctor(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantpropertyset.productvariantpropertyset(v=AX.60)
ms:contentKeyID: 62203970
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertySet.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariantPropertySet Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductVariantPropertySet](productvariantpropertyset-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    variantId As Long, _
    properties As ProductPropertyTranslationDictionary _
)
'Usage
Dim variantId As Long
Dim properties As ProductPropertyTranslationDictionary

Dim instance As New ProductVariantPropertySet(variantId, _
    properties)
```

``` csharp
public ProductVariantPropertySet(
    long variantId,
    ProductPropertyTranslationDictionary properties
)
```

``` c++
public:
ProductVariantPropertySet(
    long long variantId, 
    ProductPropertyTranslationDictionary^ properties
)
```

#### Parameters

  - variantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - properties  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary](productpropertytranslationdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductVariantPropertySet Class](productvariantpropertyset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

