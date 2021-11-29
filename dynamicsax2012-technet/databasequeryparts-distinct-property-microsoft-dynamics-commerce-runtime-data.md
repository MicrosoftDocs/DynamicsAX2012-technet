---
title: DatabaseQueryParts.Distinct Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Distinct Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.Distinct
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasequeryparts.distinct(v=AX.60)
ms:contentKeyID: 65322198
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.Distinct
dev_langs:
- CSharp
- C++
- VB
---

# Distinct Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the DISTINCT keyword is added to the query.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Distinct As Boolean
    Get
    Set
'Usage
Dim instance As DatabaseQueryParts
Dim value As Boolean

value = instance.Distinct

instance.Distinct = value
```

``` csharp
public bool Distinct { get; set; }
```

``` c++
public:
property bool Distinct {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DatabaseQueryParts Class](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

