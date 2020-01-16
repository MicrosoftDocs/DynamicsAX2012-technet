---
title: ConcurrentDictionary(TKey, TValue).Remove Method (TKey) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Remove Method (TKey)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Remove(`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn966515(v=AX.60)
ms:contentKeyID: 65316463
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Remove Method (TKey)

Removes the item for the given key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Remove ( _
    key As TKey _
) As Boolean
'Usage
Dim instance As ConcurrentDictionary
Dim key As TKey
Dim returnValue As Boolean

returnValue = instance.Remove(key)
```

``` csharp
public bool Remove(
    TKey key
)
```

``` c++
public:
virtual bool Remove(
    TKey key
) sealed
```

#### Parameters

  - key  
    Type: [TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns true if the element is removed from the dictionary successfully.  

#### Implements

[IDictionary\<TKey, TValue\>.Remove(TKey)](https://technet.microsoft.com/library/k8s489f0\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Remove Overload](concurrentdictionary-tkey-tvalue-remove-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

