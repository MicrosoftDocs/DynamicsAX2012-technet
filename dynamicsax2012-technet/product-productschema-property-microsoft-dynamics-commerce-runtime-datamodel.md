---
title: Product.ProductSchema Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductSchema Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductSchema
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.productschema(v=AX.60)
ms:contentKeyID: 62213238
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductSchema
dev_langs:
- CSharp
- C++
- VB
---

# ProductSchema Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the set of keys representing the properties of this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property ProductSchema As ICollection(Of String)
    Get
'Usage
Dim instance As Product
Dim value As ICollection(Of String)

value = instance.ProductSchema
```

``` csharp
[DataMemberAttribute]
public ICollection<string> ProductSchema { get; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<String^>^ ProductSchema {
    ICollection<String^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

