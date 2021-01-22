---
title: ConcurrentDictionary(TKey, TValue).Remove Method (KeyValuePair(TKey, TValue)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Remove Method (KeyValuePair(TKey, TValue))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Remove(System.Collections.Generic.KeyValuePair{`0,`1})
ms:mtpsurl: https://technet.microsoft.com/library/Dn987664(v=AX.60)
ms:contentKeyID: 65316217
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Remove Method (KeyValuePair(TKey, TValue))

Removes the specified item from the dictionary.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Remove ( _
    item As KeyValuePair(Of TKey, TValue) _
) As Boolean
'Usage
Dim instance As ConcurrentDictionary
Dim item As KeyValuePair(Of TKey, TValue)
Dim returnValue As Boolean

returnValue = instance.Remove(item)
```

``` csharp
public bool Remove(
    KeyValuePair<TKey, TValue> item
)
```

``` c++
public:
virtual bool Remove(
    KeyValuePair<TKey, TValue> item
) sealed
```

#### Parameters

  - item  
    Type: [System.Collections.Generic.KeyValuePair](https://technet.microsoft.com/library/5tbh8a42\(v=ax.60\))\<[TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md), [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)\>  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns the boolean after removing the item successfully.  

#### Implements

[ICollection\<T\>.Remove(T)](https://technet.microsoft.com/library/bye7h94w\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Remove Overload](concurrentdictionary-tkey-tvalue-remove-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

