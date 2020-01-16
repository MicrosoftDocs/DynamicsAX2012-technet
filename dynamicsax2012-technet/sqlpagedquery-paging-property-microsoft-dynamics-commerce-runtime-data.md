---
title: SqlPagedQuery.Paging Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Paging Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.Paging
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.paging(v=AX.60)
ms:contentKeyID: 65321266
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.Paging
dev_langs:
- CSharp
- C++
- VB
---

# Paging Property

Gets or sets the paging.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property Paging As PagingInfo
    Get
    Set
'Usage
Dim instance As SqlPagedQuery
Dim value As PagingInfo

value = instance.Paging

instance.Paging = value
```

``` csharp
public PagingInfo Paging { get; set; }
```

``` c++
public:
property PagingInfo^ Paging {
    PagingInfo^ get ();
    void set (PagingInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The paging.  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

