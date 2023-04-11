---
title: DatabaseQueryParts Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseQueryParts Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.#ctor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasequeryparts.databasequeryparts(v=AX.60)
ms:contentKeyID: 65321319
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseQueryParts Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [DatabaseQueryParts](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    columns As String, _
    schema As String, _
    fromSource As String _
)
'Usage
Dim columns As String
Dim schema As String
Dim fromSource As String

Dim instance As New DatabaseQueryParts(columns, _
    schema, fromSource)
```

``` csharp
public DatabaseQueryParts(
    string columns,
    string schema,
    string fromSource
)
```

``` c++
public:
DatabaseQueryParts(
    String^ columns, 
    String^ schema, 
    String^ fromSource
)
```

#### Parameters

  - columns  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - schema  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - fromSource  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DatabaseQueryParts Class](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

