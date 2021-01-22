---
title: ConcurrentDictionary(TKey, TValue).TryGetValue Method (TKey, Object) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TryGetValue Method (TKey, Object)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.TryGetValue(`0,System.Object@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn990900(v=AX.60)
ms:contentKeyID: 65322090
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# TryGetValue Method (TKey, Object)

Gets a value indicating whether the key is present in the dictionary or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function TryGetValue ( _
    key As TKey, _
    <OutAttribute> ByRef objValue As Object _
) As Boolean
'Usage
Dim instance As ConcurrentDictionary
Dim key As TKey
Dim objValue As Object
Dim returnValue As Boolean

returnValue = instance.TryGetValue(key, _
    objValue)
```

``` csharp
public bool TryGetValue(
    TKey key,
    out Object objValue
)
```

``` c++
public:
bool TryGetValue(
    TKey key, 
    [OutAttribute] Object^% objValue
)
```

#### Parameters

  - key  
    Type: [TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - objValue  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns the boolean value indicating whether the key is present in the dictionary.  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[TryGetValue Overload](concurrentdictionary-tkey-tvalue-trygetvalue-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

