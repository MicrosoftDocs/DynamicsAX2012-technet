---
title: ColumnSet(T) Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ColumnSet(T) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn716975(v=AX.60)
ms:contentKeyID: 62205772
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1
dev_langs:
- CSharp
- C++
- VB
---

# ColumnSet(T) Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a column set of a generic type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class ColumnSet(Of T As Class)
'Usage
Dim instance As ColumnSet(Of T)
```

``` csharp
public abstract class ColumnSet<T>
where T : class
```

``` c++
generic<typename T>
where T : ref class
public ref class ColumnSet abstract
```

#### Type Parameters

  - T

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.ColumnSet\<T\>  
    [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

