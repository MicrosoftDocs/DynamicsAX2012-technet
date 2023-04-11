---
title: ConcurrentDictionary(TKey, TValue).GetEnumerator Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEnumerator Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.GetEnumerator
ms:mtpsurl: https://technet.microsoft.com/library/Dn968680(v=AX.60)
ms:contentKeyID: 65321801
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.GetEnumerator
dev_langs:
- CSharp
- C++
- VB
---

# GetEnumerator Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the dictionary enumerator to perform enumeration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetEnumerator As IEnumerator(Of KeyValuePair(Of TKey, TValue))
'Usage
Dim instance As ConcurrentDictionary
Dim returnValue As IEnumerator(Of KeyValuePair(Of TKey, TValue))

returnValue = instance.GetEnumerator()
```

``` csharp
public IEnumerator<KeyValuePair<TKey, TValue>> GetEnumerator()
```

``` c++
public:
virtual IEnumerator<KeyValuePair<TKey, TValue>>^ GetEnumerator() sealed
```

#### Return Value

Type: [System.Collections.Generic.IEnumerator](https://technet.microsoft.com/library/78dfe2yb\(v=ax.60\))\<[KeyValuePair](https://technet.microsoft.com/library/5tbh8a42\(v=ax.60\))\<[TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md), [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)\>\>  
Returns dictionary enumeration.  

#### Implements

[IEnumerable\<T\>.GetEnumerator()](https://technet.microsoft.com/library/s793z9y2\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

