---
title: DatabaseQueryParts.Schema Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Schema Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.Schema
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasequeryparts.schema(v=AX.60)
ms:contentKeyID: 65323212
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.Schema
dev_langs:
- CSharp
- C++
- VB
---

# Schema Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a schema of a source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Schema As String
    Get
    Private Set
'Usage
Dim instance As DatabaseQueryParts
Dim value As String

value = instance.Schema
```

``` csharp
public string Schema { get; private set; }
```

``` c++
public:
property String^ Schema {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DatabaseQueryParts Class](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

