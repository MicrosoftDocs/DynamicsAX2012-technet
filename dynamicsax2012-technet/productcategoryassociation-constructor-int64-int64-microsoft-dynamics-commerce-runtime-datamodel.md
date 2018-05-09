---
title: ProductCategoryAssociation Constructor (Int64, Int64) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductCategoryAssociation Constructor (Int64, Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation.#ctor(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productcategoryassociation.productcategoryassociation(v=AX.60)
ms:contentKeyID: 62210740
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductCategoryAssociation Constructor (Int64, Int64)

Initializes a new instance of the [ProductCategoryAssociation](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productId As Long, _
    categoryId As Long _
)
'Usage
Dim productId As Long
Dim categoryId As Long

Dim instance As New ProductCategoryAssociation(productId, _
    categoryId)
```

``` csharp
public ProductCategoryAssociation(
    long productId,
    long categoryId
)
```

``` c++
public:
ProductCategoryAssociation(
    long long productId, 
    long long categoryId
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - categoryId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ProductCategoryAssociation Class](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ProductCategoryAssociation Overload](productcategoryassociation-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

