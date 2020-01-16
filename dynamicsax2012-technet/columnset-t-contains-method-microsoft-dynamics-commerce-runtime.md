---
title: ColumnSet(T).Contains Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Contains Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.Contains(`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn739185(v=AX.60)
ms:contentKeyID: 62211997
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.Contains
dev_langs:
- CSharp
- C++
- VB
---

# Contains Method

Determines whether the column set contains the specified column.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Contains ( _
    column As T _
) As Boolean
'Usage
Dim instance As ColumnSet
Dim column As T
Dim returnValue As Boolean

returnValue = instance.Contains(column)
```

``` csharp
public bool Contains(
    T column
)
```

``` c++
public:
bool Contains(
    T column
)
```

#### Parameters

  - column  
    Type: [T](columnset-t-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true, the set contains the column. Otherwise, false.  

## See Also

#### Reference

[ColumnSet\<T\> Class](columnset-t-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

