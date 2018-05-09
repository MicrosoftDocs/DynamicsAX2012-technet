---
title: ConcurrentDictionary(TKey, TValue).Contains Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Contains Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Contains(System.Collections.Generic.KeyValuePair{`0,`1})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn989160(v=AX.60)
ms:contentKeyID: 65319115
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Contains
dev_langs:
- CSharp
- C++
- VB
---

# Contains Method

Checks whether the given item exists in the dictionary.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Contains ( _
    item As KeyValuePair(Of TKey, TValue) _
) As Boolean
'Usage
Dim instance As ConcurrentDictionary
Dim item As KeyValuePair(Of TKey, TValue)
Dim returnValue As Boolean

returnValue = instance.Contains(item)
```

``` csharp
public bool Contains(
    KeyValuePair<TKey, TValue> item
)
```

``` c++
public:
virtual bool Contains(
    KeyValuePair<TKey, TValue> item
) sealed
```

#### Parameters

  - item  
    Type: [System.Collections.Generic.KeyValuePair](https://technet.microsoft.com/en-us/library/5tbh8a42\(v=ax.60\))\<[TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md), [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)\>  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns the boolean indicating whether the given item exists in dictionary.  

#### Implements

[ICollection\<T\>.Contains(T)](https://technet.microsoft.com/en-us/library/k5cf1d56\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

