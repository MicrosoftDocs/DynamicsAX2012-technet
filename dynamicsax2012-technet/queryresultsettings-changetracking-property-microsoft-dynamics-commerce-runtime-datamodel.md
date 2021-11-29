---
title: QueryResultSettings.ChangeTracking Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeTracking Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.ChangeTracking
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.queryresultsettings.changetracking(v=AX.60)
ms:contentKeyID: 65320335
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.ChangeTracking
dev_langs:
- CSharp
- C++
- VB
---

# ChangeTracking Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the information for querying changes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ChangeTracking As ChangeQueryInfo
    Get
    Private Set
'Usage
Dim instance As QueryResultSettings
Dim value As ChangeQueryInfo

value = instance.ChangeTracking
```

``` csharp
public ChangeQueryInfo ChangeTracking { get; private set; }
```

``` c++
public:
property ChangeQueryInfo^ ChangeTracking {
    ChangeQueryInfo^ get ();
    private: void set (ChangeQueryInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ChangeQueryInfo](changequeryinfo-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ChangeQueryInfo](changequeryinfo-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[QueryResultSettings Class](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

