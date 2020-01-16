---
title: Product.ProductCatalogMap Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductCatalogMap Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductCatalogMap
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.productcatalogmap(v=AX.60)
ms:contentKeyID: 65322154
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductCatalogMap
dev_langs:
- CSharp
- C++
- VB
---

# ProductCatalogMap Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ProductCatalogMap As Dictionary(Of Long, List(Of ProductCatalog))
    Get
    Private Set
'Usage
Dim instance As Product
Dim value As Dictionary(Of Long, List(Of ProductCatalog))

value = instance.ProductCatalogMap
```

``` csharp
[IgnoreDataMemberAttribute]
public Dictionary<long, List<ProductCatalog>> ProductCatalogMap { get; private set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property Dictionary<long long, List<ProductCatalog^>^>^ ProductCatalogMap {
    Dictionary<long long, List<ProductCatalog^>^>^ get ();
    private: void set (Dictionary<long long, List<ProductCatalog^>^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>\>  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

