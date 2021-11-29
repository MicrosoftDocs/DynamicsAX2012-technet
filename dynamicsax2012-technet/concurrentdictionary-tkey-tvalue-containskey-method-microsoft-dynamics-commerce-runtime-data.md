---
title: ConcurrentDictionary(TKey, TValue).ContainsKey Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ContainsKey Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.ContainsKey(`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn967553(v=AX.60)
ms:contentKeyID: 65319425
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.ContainsKey
dev_langs:
- CSharp
- C++
- VB
---

# ContainsKey Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks whether the key is present in the dictionary.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function ContainsKey ( _
    key As TKey _
) As Boolean
'Usage
Dim instance As ConcurrentDictionary
Dim key As TKey
Dim returnValue As Boolean

returnValue = instance.ContainsKey(key)
```

``` csharp
public bool ContainsKey(
    TKey key
)
```

``` c++
public:
virtual bool ContainsKey(
    TKey key
) sealed
```

#### Parameters

  - key  
    Type: [TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns true if the key is present in dictionary.  

#### Implements

[IDictionary\<TKey, TValue\>.ContainsKey(TKey)](https://technet.microsoft.com/library/htszx2dy\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

