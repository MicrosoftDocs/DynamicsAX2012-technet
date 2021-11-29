---
title: ConcurrentDictionary(TKey, TValue).AddOrUpdate Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: AddOrUpdate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.AddOrUpdate(`0,`1)
ms:mtpsurl: https://technet.microsoft.com/library/Dn988319(v=AX.60)
ms:contentKeyID: 65317364
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.AddOrUpdate
dev_langs:
- CSharp
- C++
- VB
---

# AddOrUpdate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds or Updates the value of the dictionary.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub AddOrUpdate ( _
    key As TKey, _
    value As TValue _
)
'Usage
Dim instance As ConcurrentDictionary
Dim key As TKey
Dim value As TValue

instance.AddOrUpdate(key, value)
```

``` csharp
public void AddOrUpdate(
    TKey key,
    TValue value
)
```

``` c++
public:
void AddOrUpdate(
    TKey key, 
    TValue value
)
```

#### Parameters

  - key  
    Type: [TKey](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - value  
    Type: [TValue](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

