---
title: QueryResultSettings.ColumnSet Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ColumnSet Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.ColumnSet
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.queryresultsettings.columnset(v=AX.60)
ms:contentKeyID: 65317299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.ColumnSet
dev_langs:
- CSharp
- C++
- VB
---

# ColumnSet Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the column set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ColumnSet As ColumnSet
    Get
    Private Set
'Usage
Dim instance As QueryResultSettings
Dim value As ColumnSet

value = instance.ColumnSet
```

``` csharp
public ColumnSet ColumnSet { get; private set; }
```

``` c++
public:
property ColumnSet^ ColumnSet {
    ColumnSet^ get ();
    private: void set (ColumnSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[QueryResultSettings Class](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

