---
title: ProductCategoryAssociation.IsPrimaryCategory Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPrimaryCategory Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation.IsPrimaryCategory
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcategoryassociation.isprimarycategory(v=AX.60)
ms:contentKeyID: 62203267
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation.IsPrimaryCategory
dev_langs:
- CSharp
- C++
- VB
---

# IsPrimaryCategory Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether this is a primary category for the associated product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsPrimaryCategory As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductCategoryAssociation
Dim value As Boolean

value = instance.IsPrimaryCategory
```

``` csharp
[DataMemberAttribute]
public bool IsPrimaryCategory { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsPrimaryCategory {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductCategoryAssociation Class](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

