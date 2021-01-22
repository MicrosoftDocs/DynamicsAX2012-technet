---
title: ConcurrentDictionary(TKey, TValue).TryGetValue Method (TKey, TValue) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TryGetValue Method (TKey, TValue)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.TryGetValue(`0,`1@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn966457(v=AX.60)
ms:contentKeyID: 65316405
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# TryGetValue Method (TKey, TValue)

Gets a value indicating whether the key is present in the dictionary or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function TryGetValue ( _
    key As TKey, _
    <OutAttribute> ByRef value As TValue _
) As Boolean
'Usage
Dim instance As ConcurrentDictionary
Dim key As TKey
Dim value As TValue
Dim returnValue As Boolean

returnValue = instance.TryGetValue(key, _
    value)
```

``` csharp
public bool TryGetValue(
    TKey key,
    out TValue value
)
```

``` c++
public:
virtual bool TryGetValue(
    TKey key, 
    [OutAttribute] TValue% value
) sealed
```

#### Parameters

  - key  
    Type: [TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - value  
    Type: [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns the boolean value indicating whether the key is present in the dictionary.  

#### Implements

[IDictionary\<TKey, TValue\>.TryGetValue(TKey, TValue)](https://technet.microsoft.com/library/bb299639\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[TryGetValue Overload](concurrentdictionary-tkey-tvalue-trygetvalue-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

