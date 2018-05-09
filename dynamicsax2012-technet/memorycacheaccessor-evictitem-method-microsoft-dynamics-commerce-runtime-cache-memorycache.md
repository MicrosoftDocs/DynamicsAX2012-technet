---
title: MemoryCacheAccessor.EvictItem Method  (Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache)
TOCTitle: EvictItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.EvictItem(System.String,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.cache.memorycache.memorycacheaccessor.evictitem(v=AX.60)
ms:contentKeyID: 65321342
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.EvictItem
dev_langs:
- CSharp
- C++
- VB
---

# EvictItem Method

Evicts from the cache the item with the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.dll)

## Syntax

``` vb
'Declaration
Public Sub EvictItem ( _
    key As String, _
    currentStore As IDataStore _
)
'Usage
Dim instance As MemoryCacheAccessor
Dim key As String
Dim currentStore As IDataStore

instance.EvictItem(key, currentStore)
```

``` csharp
public void EvictItem(
    string key,
    IDataStore currentStore
)
```

``` c++
public:
virtual void EvictItem(
    String^ key, 
    IDataStore^ currentStore
) sealed
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[IKeyedDataStoreAccessor.EvictItem(String, IDataStore)](ikeyeddatastoreaccessor-evictitem-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[MemoryCacheAccessor Class](memorycacheaccessor-class-microsoft-dynamics-commerce-runtime-cache-memorycache.md)

[Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache Namespace](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)

