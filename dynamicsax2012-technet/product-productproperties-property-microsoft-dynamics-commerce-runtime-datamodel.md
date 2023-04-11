---
title: Product.ProductProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.productproperties(v=AX.60)
ms:contentKeyID: 62208385
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductProperties
dev_langs:
- CSharp
- C++
- VB
---

# ProductProperties Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of translated properties as a flat list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property ProductProperties As ICollection(Of ProductPropertyTranslation)
    Get
'Usage
Dim instance As Product
Dim value As ICollection(Of ProductPropertyTranslation)

value = instance.ProductProperties
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductPropertyTranslation> ProductProperties { get; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductPropertyTranslation^>^ ProductProperties {
    ICollection<ProductPropertyTranslation^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductPropertyTranslation](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

