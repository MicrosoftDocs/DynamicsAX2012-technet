---
title: Product.AddRelatedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddRelatedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.AddRelatedProducts(System.Collections.Generic.IList{Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct},System.Collections.Generic.IList{Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.addrelatedproducts(v=AX.60)
ms:contentKeyID: 65321373
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.AddRelatedProducts
dev_langs:
- CSharp
- C++
- VB
---

# AddRelatedProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddRelatedProducts ( _
    relatedProducts As IList(Of RelatedProduct), _
    productsRelatedToThis As IList(Of RelatedProduct) _
)
'Usage
Dim instance As Product
Dim relatedProducts As IList(Of RelatedProduct)
Dim productsRelatedToThis As IList(Of RelatedProduct)

instance.AddRelatedProducts(relatedProducts, _
    productsRelatedToThis)
```

``` csharp
public void AddRelatedProducts(
    IList<RelatedProduct> relatedProducts,
    IList<RelatedProduct> productsRelatedToThis
)
```

``` c++
public:
void AddRelatedProducts(
    IList<RelatedProduct^>^ relatedProducts, 
    IList<RelatedProduct^>^ productsRelatedToThis
)
```

#### Parameters

  - relatedProducts  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[RelatedProduct](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - productsRelatedToThis  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[RelatedProduct](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

