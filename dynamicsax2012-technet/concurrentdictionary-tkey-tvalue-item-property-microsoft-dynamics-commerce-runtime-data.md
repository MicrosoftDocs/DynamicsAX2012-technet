---
title: ConcurrentDictionary(TKey, TValue).Item Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Item Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Item(`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn967026(v=AX.60)
ms:contentKeyID: 65317886
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Item
dev_langs:
- CSharp
- C++
- VB
---

# Item Property

The index of the dictionary key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Item ( _
    key As TKey _
) As TValue
    Get
    Set
'Usage
Dim instance As ConcurrentDictionary
Dim key As TKey
Dim value As TValue

value = instance.Item(key)

instance.Item(key) = value
```

``` csharp
public TValue this[
    TKey key
] { get; set; }
```

``` c++
public:
virtual property TValue Item[TKey key] {
    TValue get (TKey key) sealed;
    void set (TKey key, TValue value) sealed;
}
```

#### Parameters

  - key  
    Type: [TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Property Value

Type: [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  
Returns the value of the dictionary.  

#### Implements

[IDictionary\<TKey, TValue\>.Item\[TKey\]](https://technet.microsoft.com/library/zyxt2e2h\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

