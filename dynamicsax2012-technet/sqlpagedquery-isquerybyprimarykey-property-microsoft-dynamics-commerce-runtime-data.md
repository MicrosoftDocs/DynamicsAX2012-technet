---
title: SqlPagedQuery.IsQueryByPrimaryKey Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsQueryByPrimaryKey Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.IsQueryByPrimaryKey
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.isquerybyprimarykey(v=AX.60)
ms:contentKeyID: 65318257
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.IsQueryByPrimaryKey
dev_langs:
- CSharp
- C++
- VB
---

# IsQueryByPrimaryKey Property

Gets or sets a value indicating whether this query is by primary key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property IsQueryByPrimaryKey As Boolean
    Get
    Set
'Usage
Dim instance As SqlPagedQuery
Dim value As Boolean

value = instance.IsQueryByPrimaryKey

instance.IsQueryByPrimaryKey = value
```

``` csharp
public bool IsQueryByPrimaryKey { get; set; }
```

``` c++
public:
property bool IsQueryByPrimaryKey {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
If true the query is expected to return only a single record; otherwise, false.  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

