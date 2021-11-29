---
title: CatalogSearchCriteria.ProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria.ProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.catalogsearchcriteria.productids(v=AX.60)
ms:contentKeyID: 62210321
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria.ProductIds
dev_langs:
- CSharp
- C++
- VB
---

# ProductIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the ids of the products by which to search for catalogs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductIds As IList(Of Long)
    Get
    Set
'Usage
Dim instance As CatalogSearchCriteria
Dim value As IList(Of Long)

value = instance.ProductIds

instance.ProductIds = value
```

``` csharp
[DataMemberAttribute]
public IList<long> ProductIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<long long>^ ProductIds {
    IList<long long>^ get ();
    void set (IList<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[CatalogSearchCriteria Class](catalogsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

