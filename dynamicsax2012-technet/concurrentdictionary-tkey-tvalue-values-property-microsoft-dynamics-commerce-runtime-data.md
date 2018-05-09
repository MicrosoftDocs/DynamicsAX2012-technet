---
title: ConcurrentDictionary(TKey, TValue).Values Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Values Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Values
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn988309(v=AX.60)
ms:contentKeyID: 65317355
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Values
dev_langs:
- CSharp
- C++
- VB
---

# Values Property

Gets the collection of dictionary values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Values As ICollection(Of TValue)
    Get
'Usage
Dim instance As ConcurrentDictionary
Dim value As ICollection(Of TValue)

value = instance.Values
```

``` csharp
public ICollection<TValue> Values { get; }
```

``` c++
public:
virtual property ICollection<TValue>^ Values {
    ICollection<TValue>^ get () sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

#### Implements

[IDictionary\<TKey, TValue\>.Values](https://technet.microsoft.com/en-us/library/0yxt5h4s\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

