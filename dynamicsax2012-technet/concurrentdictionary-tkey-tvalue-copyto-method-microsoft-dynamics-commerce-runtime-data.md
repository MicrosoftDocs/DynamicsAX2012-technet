---
title: ConcurrentDictionary(TKey, TValue).CopyTo Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CopyTo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.CopyTo(System.Collections.Generic.KeyValuePair{`0,`1}[],System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/Dn967882(v=AX.60)
ms:contentKeyID: 65319742
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.CopyTo
dev_langs:
- CSharp
- C++
- VB
---

# CopyTo Method

Copies the elements of dictionary to the array starting at particular index.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub CopyTo ( _
    array As KeyValuePair(Of TKey, TValue)(), _
    arrayIndex As Integer _
)
'Usage
Dim instance As ConcurrentDictionary
Dim array As KeyValuePair(Of TKey, TValue)()
Dim arrayIndex As Integer

instance.CopyTo(array, arrayIndex)
```

``` csharp
public void CopyTo(
    KeyValuePair<TKey, TValue>[] array,
    int arrayIndex
)
```

``` c++
public:
virtual void CopyTo(
    array<KeyValuePair<TKey, TValue>>^ array, 
    int arrayIndex
) sealed
```

#### Parameters

  - array  
    Type: [System.Collections.Generic.KeyValuePair](https://technet.microsoft.com/library/5tbh8a42\(v=ax.60\))\<[TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md), [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)\>\[\]  

<!-- end list -->

  - arrayIndex  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Implements

[ICollection\<T\>.CopyTo(T\[\], Int32)](https://technet.microsoft.com/library/0efx51xw\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

