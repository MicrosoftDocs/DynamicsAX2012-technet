---
title: ProductSearchCriteria.IncludeProductsFromDescendantCategories Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IncludeProductsFromDescendantCategories Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.IncludeProductsFromDescendantCategories
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.includeproductsfromdescendantcategories(v=AX.60)
ms:contentKeyID: 65317300
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.IncludeProductsFromDescendantCategories
dev_langs:
- CSharp
- C++
- VB
---

# IncludeProductsFromDescendantCategories Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncludeProductsFromDescendantCategories As Boolean
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As Boolean

value = instance.IncludeProductsFromDescendantCategories

instance.IncludeProductsFromDescendantCategories = value
```

``` csharp
[DataMemberAttribute]
public bool IncludeProductsFromDescendantCategories { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IncludeProductsFromDescendantCategories {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

