---
title: ProjectionDomain.CatalogId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain.CatalogId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.projectiondomain.catalogid(v=AX.60)
ms:contentKeyID: 62211060
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the catalog identifier of this context.

There are three values possible for Catalog id : a) 0 - all active catalogs, b) a specific catalog id or c) null - no catalog id passed (for sharepoint).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CatalogId As Nullable(Of Long)
    Get
    Set
'Usage
Dim instance As ProjectionDomain
Dim value As Nullable(Of Long)

value = instance.CatalogId

instance.CatalogId = value
```

``` csharp
[DataMemberAttribute]
public Nullable<long> CatalogId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<long long> CatalogId {
    Nullable<long long> get ();
    void set (Nullable<long long> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[ProjectionDomain Class](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

