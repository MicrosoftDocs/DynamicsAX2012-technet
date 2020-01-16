---
title: ColumnSet Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ColumnSet Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.ColumnSet
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.columnset(v=AX.60)
ms:contentKeyID: 49839132
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ColumnSet
dev_langs:
- CSharp
- C++
- VB
---

# ColumnSet Class

Represents the collection of columns that should be retrieved by the query.

If no columns have been specified, all columns are retrieved by default.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ColumnSet _
    Inherits ColumnSet(Of String)
'Usage
Dim instance As ColumnSet
```

``` csharp
public sealed class ColumnSet : ColumnSet<string>
```

``` c++
public ref class ColumnSet sealed : public ColumnSet<String^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-t-class-microsoft-dynamics-commerce-runtime.md)\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
    Microsoft.Dynamics.Commerce.Runtime.ColumnSet  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

