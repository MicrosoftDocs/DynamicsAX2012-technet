---
title: SqlPagedQuery.Aliased Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Aliased Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.Aliased
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.aliased(v=AX.60)
ms:contentKeyID: 65320124
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.Aliased
dev_langs:
- CSharp
- C++
- VB
---

# Aliased Property

Gets or sets a value indicating whether a query source should have an alias.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property Aliased As Boolean
    Get
    Set
'Usage
Dim instance As SqlPagedQuery
Dim value As Boolean

value = instance.Aliased

instance.Aliased = value
```

``` csharp
public bool Aliased { get; set; }
```

``` c++
public:
property bool Aliased {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

