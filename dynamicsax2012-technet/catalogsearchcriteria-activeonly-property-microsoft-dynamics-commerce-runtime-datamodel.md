---
title: CatalogSearchCriteria.ActiveOnly Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ActiveOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria.ActiveOnly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.catalogsearchcriteria.activeonly(v=AX.60)
ms:contentKeyID: 62206902
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria.ActiveOnly
dev_langs:
- CSharp
- C++
- VB
---

# ActiveOnly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the query should return only active catalogs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActiveOnly As Boolean
    Get
    Set
'Usage
Dim instance As CatalogSearchCriteria
Dim value As Boolean

value = instance.ActiveOnly

instance.ActiveOnly = value
```

``` csharp
[DataMemberAttribute]
public bool ActiveOnly { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool ActiveOnly {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CatalogSearchCriteria Class](catalogsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

