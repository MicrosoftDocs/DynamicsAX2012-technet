---
title: ProductSearchCriteria.ItemIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.ItemIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.itemids(v=AX.60)
ms:contentKeyID: 62202851
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.ItemIds
dev_langs:
- CSharp
- C++
- VB
---

# ItemIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the set of item ids by which to search for products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemIds As IList(Of ProductLookupClause)
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As IList(Of ProductLookupClause)

value = instance.ItemIds

instance.ItemIds = value
```

``` csharp
[DataMemberAttribute]
public IList<ProductLookupClause> ItemIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<ProductLookupClause^>^ ItemIds {
    IList<ProductLookupClause^>^ get ();
    void set (IList<ProductLookupClause^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ProductLookupClause](productlookupclause-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

