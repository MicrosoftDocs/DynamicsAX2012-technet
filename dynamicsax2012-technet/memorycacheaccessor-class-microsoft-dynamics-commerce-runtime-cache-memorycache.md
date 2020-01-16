---
title: MemoryCacheAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache)
TOCTitle: MemoryCacheAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cache.memorycache.memorycacheaccessor(v=AX.60)
ms:contentKeyID: 65320920
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor
dev_langs:
- CSharp
- C++
- VB
---

# MemoryCacheAccessor Class

Class modeling the behavior of a memory cache accessor.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.dll)

## Syntax

``` vb
'Declaration
<CacheAttribute("CacheProvider")> _
Public Class MemoryCacheAccessor _
    Implements IKeyedDataStoreAccessor
'Usage
Dim instance As MemoryCacheAccessor
```

``` csharp
[CacheAttribute("CacheProvider")]
public class MemoryCacheAccessor : IKeyedDataStoreAccessor
```

``` c++
[CacheAttribute(L"CacheProvider")]
public ref class MemoryCacheAccessor : IKeyedDataStoreAccessor
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache Namespace](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)

