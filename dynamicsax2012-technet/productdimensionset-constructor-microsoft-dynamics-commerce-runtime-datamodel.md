---
title: ProductDimensionSet Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductDimensionSet Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionSet.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueDictionary)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensionset.productdimensionset(v=AX.60)
ms:contentKeyID: 62214418
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionSet.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ProductDimensionSet Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductDimensionSet](productdimensionset-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    dimensionKey As String, _
    indexedDimensionValues As ProductDimensionValueDictionary _
)
'Usage
Dim dimensionKey As String
Dim indexedDimensionValues As ProductDimensionValueDictionary

Dim instance As New ProductDimensionSet(dimensionKey, _
    indexedDimensionValues)
```

``` csharp
public ProductDimensionSet(
    string dimensionKey,
    ProductDimensionValueDictionary indexedDimensionValues
)
```

``` c++
public:
ProductDimensionSet(
    String^ dimensionKey, 
    ProductDimensionValueDictionary^ indexedDimensionValues
)
```

#### Parameters

  - dimensionKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - indexedDimensionValues  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueDictionary](productdimensionvaluedictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductDimensionSet Class](productdimensionset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

