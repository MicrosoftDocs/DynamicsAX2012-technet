---
title: ColumnSet(T).GetEnumerator Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetEnumerator Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.GetEnumerator
ms:mtpsurl: https://technet.microsoft.com/library/Dn718701(v=AX.60)
ms:contentKeyID: 62213821
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.GetEnumerator
dev_langs:
- CSharp
- C++
- VB
---

# GetEnumerator Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns an enumerator that iterates through the collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetEnumerator As List<T>.Enumerator
'Usage
Dim instance As ColumnSet
Dim returnValue As List<T>.Enumerator

returnValue = instance.GetEnumerator()
```

``` csharp
public List<T>.Enumerator GetEnumerator()
```

``` c++
public:
List<T>.Enumerator GetEnumerator()
```

#### Return Value

Type: [System.Collections.Generic.List\<T\>.Enumerator](https://technet.microsoft.com/library/x854yt9s\(v=ax.60\))  
An enumerator that can be used to iterate through the collection.  

## See Also

#### Reference

[ColumnSet\<T\> Class](columnset-t-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

