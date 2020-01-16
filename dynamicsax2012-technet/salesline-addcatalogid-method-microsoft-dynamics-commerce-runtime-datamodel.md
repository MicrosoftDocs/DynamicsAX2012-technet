---
title: SalesLine.AddCatalogId Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddCatalogId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.AddCatalogId(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.addcatalogid(v=AX.60)
ms:contentKeyID: 62207041
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.AddCatalogId
dev_langs:
- CSharp
- C++
- VB
---

# AddCatalogId Method

Adds a catalog id to the set of catalogs the product is included in.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function AddCatalogId ( _
    catalogId As Long _
) As Boolean
'Usage
Dim instance As SalesLine
Dim catalogId As Long
Dim returnValue As Boolean

returnValue = instance.AddCatalogId(catalogId)
```

``` csharp
public bool AddCatalogId(
    long catalogId
)
```

``` c++
public:
bool AddCatalogId(
    long long catalogId
)
```

#### Parameters

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the catalog was successfully added, otherwise false.  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

