---
title: SqlPagedQuery.DatabaseSchema Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseSchema Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.DatabaseSchema
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.databaseschema(v=AX.60)
ms:contentKeyID: 65316761
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.DatabaseSchema
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseSchema Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the database schema.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property DatabaseSchema As String
    Get
    Set
'Usage
Dim instance As SqlPagedQuery
Dim value As String

value = instance.DatabaseSchema

instance.DatabaseSchema = value
```

``` csharp
public string DatabaseSchema { get; set; }
```

``` c++
public:
property String^ DatabaseSchema {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

