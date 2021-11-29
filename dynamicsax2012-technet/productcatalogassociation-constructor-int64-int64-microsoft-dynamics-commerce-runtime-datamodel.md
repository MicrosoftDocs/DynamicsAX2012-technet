---
title: ProductCatalogAssociation Constructor (Int64, Int64) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductCatalogAssociation Constructor (Int64, Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalogAssociation.#ctor(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcatalogassociation.productcatalogassociation(v=AX.60)
ms:contentKeyID: 62212089
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductCatalogAssociation Constructor (Int64, Int64)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductCatalogAssociation](productcatalogassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productId As Long, _
    catalogId As Long _
)
'Usage
Dim productId As Long
Dim catalogId As Long

Dim instance As New ProductCatalogAssociation(productId, _
    catalogId)
```

``` csharp
public ProductCatalogAssociation(
    long productId,
    long catalogId
)
```

``` c++
public:
ProductCatalogAssociation(
    long long productId, 
    long long catalogId
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ProductCatalogAssociation Class](productcatalogassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ProductCatalogAssociation Overload](productcatalogassociation-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

