---
title: ColumnSet(T).Add Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Add Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.Add(`0[])
ms:mtpsurl: https://technet.microsoft.com/library/Dn739375(v=AX.60)
ms:contentKeyID: 62212439
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.Add
dev_langs:
- CSharp
- C++
- VB
---

# Add Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds the collection of columns to the set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub Add ( _
    ParamArray columns As T() _
)
'Usage
Dim instance As ColumnSet
Dim columns As T()

instance.Add(columns)
```

``` csharp
public void Add(
    params T[] columns
)
```

``` c++
public:
void Add(
    ... array<T>^ columns
)
```

#### Parameters

  - columns  
    Type: [T](columnset-t-class-microsoft-dynamics-commerce-runtime.md)\[\]  

## See Also

#### Reference

[ColumnSet\<T\> Class](columnset-t-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

