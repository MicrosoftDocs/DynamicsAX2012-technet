---
title: ConcurrentDictionary(TKey, TValue).IDictionary(TKey, TValue).Keys Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IDictionary(TKey, TValue).Keys Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.System#Collections#Generic#IDictionary{TKey@TValue}#Keys
ms:mtpsurl: https://technet.microsoft.com/library/Dn990279(v=AX.60)
ms:contentKeyID: 65321221
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- IDictionary.Keys
- ConcurrentDictionary`2.IDictionary.Keys
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.IDictionary.Keys
dev_langs:
- CSharp
- C++
- VB
---

# IDictionary(TKey, TValue).Keys Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of dictionary keys.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Private ReadOnly Property Keys As ICollection(Of TKey)
    Implements IDictionary(Of TKey, TValue).Keys
    Get
'Usage
Dim instance As ConcurrentDictionary
Dim value As ICollection(Of TKey)

value = CType(instance, IDictionary(Of TKey, TValue)).Keys
```

``` csharp
ICollection<TKey> IDictionary<TKey, TValue>.Keys { get; }
```

``` c++
private:
virtual property ICollection<TKey>^ Keys {
    ICollection<TKey>^ get () sealed = IDictionary<TKey, TValue>::Keys::get;
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

#### Implements

[IDictionary\<TKey, TValue\>.Keys](https://technet.microsoft.com/library/1ebzfbyx\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

