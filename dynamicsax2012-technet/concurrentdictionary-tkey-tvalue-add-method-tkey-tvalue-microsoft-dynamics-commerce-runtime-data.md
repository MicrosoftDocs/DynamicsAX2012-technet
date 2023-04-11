---
title: ConcurrentDictionary(TKey, TValue).Add Method (TKey, TValue) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Add Method (TKey, TValue)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Add(`0,`1)
ms:mtpsurl: https://technet.microsoft.com/library/Dn968742(v=AX.60)
ms:contentKeyID: 65321863
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Add Method (TKey, TValue)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Add the dictionary value for the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub Add ( _
    key As TKey, _
    value As TValue _
)
'Usage
Dim instance As ConcurrentDictionary
Dim key As TKey
Dim value As TValue

instance.Add(key, value)
```

``` csharp
public void Add(
    TKey key,
    TValue value
)
```

``` c++
public:
virtual void Add(
    TKey key, 
    TValue value
) sealed
```

#### Parameters

  - key  
    Type: [TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - value  
    Type: [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[IDictionary\<TKey, TValue\>.Add(TKey, TValue)](https://technet.microsoft.com/library/cy7xta5e\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Add Overload](concurrentdictionary-tkey-tvalue-add-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

