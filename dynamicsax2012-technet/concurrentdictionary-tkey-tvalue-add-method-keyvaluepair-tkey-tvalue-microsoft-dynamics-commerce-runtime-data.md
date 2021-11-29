---
title: ConcurrentDictionary(TKey, TValue).Add Method (KeyValuePair(TKey, TValue)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Add Method (KeyValuePair(TKey, TValue))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Add(System.Collections.Generic.KeyValuePair{`0,`1})
ms:mtpsurl: https://technet.microsoft.com/library/Dn988675(v=AX.60)
ms:contentKeyID: 65318226
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Add Method (KeyValuePair(TKey, TValue))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds the key/value pair item to the dictionary.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub Add ( _
    item As KeyValuePair(Of TKey, TValue) _
)
'Usage
Dim instance As ConcurrentDictionary
Dim item As KeyValuePair(Of TKey, TValue)

instance.Add(item)
```

``` csharp
public void Add(
    KeyValuePair<TKey, TValue> item
)
```

``` c++
public:
virtual void Add(
    KeyValuePair<TKey, TValue> item
) sealed
```

#### Parameters

  - item  
    Type: [System.Collections.Generic.KeyValuePair](https://technet.microsoft.com/library/5tbh8a42\(v=ax.60\))\<[TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md), [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)\>  

#### Implements

[ICollection\<T\>.Add(T)](https://technet.microsoft.com/library/63ywd54z\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Add Overload](concurrentdictionary-tkey-tvalue-add-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

