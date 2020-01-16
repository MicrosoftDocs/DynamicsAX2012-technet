---
title: QueryResultSettings.Default Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Default Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.Default
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.queryresultsettings.default(v=AX.60)
ms:contentKeyID: 65317053
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.Default
dev_langs:
- CSharp
- C++
- VB
---

# Default Property

Gets the default query result settings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property Default As QueryResultSettings
    Get
'Usage
Dim value As QueryResultSettings

value = QueryResultSettings.Default
```

``` csharp
public static QueryResultSettings Default { get; }
```

``` c++
public:
static property QueryResultSettings^ Default {
    QueryResultSettings^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[QueryResultSettings Class](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

