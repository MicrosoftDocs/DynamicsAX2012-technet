---
title: MemoryCacheAccessor.EvictAll Method  (Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache)
TOCTitle: EvictAll Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.EvictAll(System.String,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cache.memorycache.memorycacheaccessor.evictall(v=AX.60)
ms:contentKeyID: 65321738
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.EvictAll
dev_langs:
- CSharp
- C++
- VB
---

# EvictAll Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Evicts all the items from the cache.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.dll)

## Syntax

``` vb
'Declaration
Public Sub EvictAll ( _
    keyPattern As String, _
    currentStore As IDataStore _
)
'Usage
Dim instance As MemoryCacheAccessor
Dim keyPattern As String
Dim currentStore As IDataStore

instance.EvictAll(keyPattern, currentStore)
```

``` csharp
public void EvictAll(
    string keyPattern,
    IDataStore currentStore
)
```

``` c++
public:
virtual void EvictAll(
    String^ keyPattern, 
    IDataStore^ currentStore
) sealed
```

#### Parameters

  - keyPattern  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[IKeyedDataStoreAccessor.EvictAll(String, IDataStore)](ikeyeddatastoreaccessor-evictall-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[MemoryCacheAccessor Class](memorycacheaccessor-class-microsoft-dynamics-commerce-runtime-cache-memorycache.md)

[Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache Namespace](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)

