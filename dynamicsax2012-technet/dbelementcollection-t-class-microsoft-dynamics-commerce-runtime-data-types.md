---
title: DbElementCollection(T) Class (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: DbElementCollection(T) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn998416(v=AX.60)
ms:contentKeyID: 65315833
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1
dev_langs:
- CSharp
- C++
- VB
---

# DbElementCollection(T) Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a collection of database elements.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class DbElementCollection(Of T) _
    Implements ICollection, IList(Of T), ICollection(Of T),  _
    IEnumerable(Of T), IEnumerable
'Usage
Dim instance As DbElementCollection(Of T)
```

``` csharp
public abstract class DbElementCollection<T> : ICollection, 
    IList<T>, ICollection<T>, IEnumerable<T>, IEnumerable
```

``` c++
generic<typename T>
public ref class DbElementCollection abstract : ICollection, 
    IList<T>, ICollection<T>, IEnumerable<T>, IEnumerable
```

#### Type Parameters

  - T

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection\<T\>  
    [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumnCollection](datacolumncollection-class-microsoft-dynamics-commerce-runtime-data-types.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRowCollection](datarowcollection-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

