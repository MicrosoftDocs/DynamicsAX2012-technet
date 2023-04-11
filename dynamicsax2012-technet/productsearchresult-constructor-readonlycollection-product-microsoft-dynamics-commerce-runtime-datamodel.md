---
title: ProductSearchResult Constructor (ReadOnlyCollection(Product)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductSearchResult Constructor (ReadOnlyCollection(Product))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Product})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchresult.productsearchresult(v=AX.60)
ms:contentKeyID: 62214126
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductSearchResult Constructor (ReadOnlyCollection(Product))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    products As ReadOnlyCollection(Of Product) _
)
'Usage
Dim products As ReadOnlyCollection(Of Product)

Dim instance As New ProductSearchResult(products)
```

``` csharp
public ProductSearchResult(
    ReadOnlyCollection<Product> products
)
```

``` c++
public:
ProductSearchResult(
    ReadOnlyCollection<Product^>^ products
)
```

#### Parameters

  - products  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductSearchResult Class](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ProductSearchResult Overload](productsearchresult-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

