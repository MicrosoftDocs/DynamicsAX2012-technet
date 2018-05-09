---
title: ConcurrentDictionary(TKey, TValue) Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ConcurrentDictionary(TKey, TValue) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn990182(v=AX.60)
ms:contentKeyID: 65320871
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrentDictionary(TKey, TValue) Class

The thread safe implementation of dictionary operations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ConcurrentDictionary(Of TKey, TValue) _
    Implements IDictionary(Of TKey, TValue), ICollection(Of KeyValuePair(Of TKey, TValue)),  _
    IEnumerable(Of KeyValuePair(Of TKey, TValue)), IEnumerable
'Usage
Dim instance As ConcurrentDictionary(Of TKey, TValue)
```

``` csharp
public sealed class ConcurrentDictionary<TKey, TValue> : IDictionary<TKey, TValue>, 
    ICollection<KeyValuePair<TKey, TValue>>, IEnumerable<KeyValuePair<TKey, TValue>>, 
    IEnumerable
```

``` c++
generic<typename TKey, typename TValue>
public ref class ConcurrentDictionary sealed : IDictionary<TKey, TValue>, 
    ICollection<KeyValuePair<TKey, TValue>>, IEnumerable<KeyValuePair<TKey, TValue>>, 
    IEnumerable
```

#### Type Parameters

  - TKey

<!-- end list -->

  - TValue

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary\<TKey, TValue\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

