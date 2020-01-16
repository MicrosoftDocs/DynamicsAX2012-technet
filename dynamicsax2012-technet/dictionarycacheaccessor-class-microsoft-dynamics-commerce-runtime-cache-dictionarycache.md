---
title: DictionaryCacheAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache)
TOCTitle: DictionaryCacheAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.DictionaryCacheAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cache.dictionarycache.dictionarycacheaccessor(v=AX.60)
ms:contentKeyID: 65321587
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.DictionaryCacheAccessor
dev_langs:
- CSharp
- C++
- VB
---

# DictionaryCacheAccessor Class

Class modeling the behavior of a offline cache accessor.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache](microsoft-dynamics-commerce-runtime-cache-dictionarycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.dll)

## Syntax

``` vb
'Declaration
<CacheAttribute("CacheProvider")> _
Public Class DictionaryCacheAccessor _
    Implements IKeyedDataStoreAccessor
'Usage
Dim instance As DictionaryCacheAccessor
```

``` csharp
[CacheAttribute("CacheProvider")]
public class DictionaryCacheAccessor : IKeyedDataStoreAccessor
```

``` c++
[CacheAttribute(L"CacheProvider")]
public ref class DictionaryCacheAccessor : IKeyedDataStoreAccessor
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.DictionaryCacheAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache Namespace](microsoft-dynamics-commerce-runtime-cache-dictionarycache-namespace.md)

