---
title: ProductSearchCriteria.CategoryIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.CategoryIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.categoryids(v=AX.60)
ms:contentKeyID: 62211971
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.CategoryIds
dev_langs:
- CSharp
- C++
- VB
---

# CategoryIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the category ids by which to retrieve products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CategoryIds As IList(Of Long)
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As IList(Of Long)

value = instance.CategoryIds

instance.CategoryIds = value
```

``` csharp
[DataMemberAttribute]
public IList<long> CategoryIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<long long>^ CategoryIds {
    IList<long long>^ get ();
    void set (IList<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

