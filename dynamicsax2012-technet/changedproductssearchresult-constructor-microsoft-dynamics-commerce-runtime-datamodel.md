---
title: ChangedProductsSearchResult Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangedProductsSearchResult Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchResult.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Product})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.changedproductssearchresult.changedproductssearchresult(v=AX.60)
ms:contentKeyID: 62212094
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchResult.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ChangedProductsSearchResult Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ChangedProductsSearchResult](changedproductssearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    products As IEnumerable(Of Product) _
)
'Usage
Dim products As IEnumerable(Of Product)

Dim instance As New ChangedProductsSearchResult(products)
```

``` csharp
public ChangedProductsSearchResult(
    IEnumerable<Product> products
)
```

``` c++
public:
ChangedProductsSearchResult(
    IEnumerable<Product^>^ products
)
```

#### Parameters

  - products  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChangedProductsSearchResult Class](changedproductssearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

