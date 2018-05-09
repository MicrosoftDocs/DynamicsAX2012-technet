---
title: ConcurrentDictionary(TKey, TValue).Keys Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Keys Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Keys
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn968122(v=AX.60)
ms:contentKeyID: 65320486
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Keys
dev_langs:
- CSharp
- C++
- VB
---

# Keys Method

Gets the collection of dictionary keys.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Keys As ICollection(Of TKey)
'Usage
Dim instance As ConcurrentDictionary
Dim returnValue As ICollection(Of TKey)

returnValue = instance.Keys()
```

``` csharp
public ICollection<TKey> Keys()
```

``` c++
public:
ICollection<TKey>^ Keys()
```

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)\>  
Returns the collection of dictionary keys.  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

