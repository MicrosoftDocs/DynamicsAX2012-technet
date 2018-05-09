---
title: Product.RelatedProducts Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RelatedProducts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.RelatedProducts
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.relatedproducts(v=AX.60)
ms:contentKeyID: 62213338
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.RelatedProducts
dev_langs:
- CSharp
- C++
- VB
---

# RelatedProducts Property

Gets information about the products related to the this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RelatedProducts As ICollection(Of RelatedProduct)
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As ICollection(Of RelatedProduct)

value = instance.RelatedProducts
```

``` csharp
[DataMemberAttribute]
public ICollection<RelatedProduct> RelatedProducts { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<RelatedProduct^>^ RelatedProducts {
    ICollection<RelatedProduct^>^ get ();
    internal: void set (ICollection<RelatedProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[RelatedProduct](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

