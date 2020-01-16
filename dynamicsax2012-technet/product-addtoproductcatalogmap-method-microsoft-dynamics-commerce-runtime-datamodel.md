---
title: Product.AddToProductCatalogMap Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddToProductCatalogMap Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.AddToProductCatalogMap(System.Int64,System.Collections.Generic.List{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.addtoproductcatalogmap(v=AX.60)
ms:contentKeyID: 65320631
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.AddToProductCatalogMap
dev_langs:
- CSharp
- C++
- VB
---

# AddToProductCatalogMap Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddToProductCatalogMap ( _
    key As Long, _
    catalogs As List(Of ProductCatalog) _
)
'Usage
Dim instance As Product
Dim key As Long
Dim catalogs As List(Of ProductCatalog)

instance.AddToProductCatalogMap(key, _
    catalogs)
```

``` csharp
public void AddToProductCatalogMap(
    long key,
    List<ProductCatalog> catalogs
)
```

``` c++
public:
void AddToProductCatalogMap(
    long long key, 
    List<ProductCatalog^>^ catalogs
)
```

#### Parameters

  - key  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogs  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

