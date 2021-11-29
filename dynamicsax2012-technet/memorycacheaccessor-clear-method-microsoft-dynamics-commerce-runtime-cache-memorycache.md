---
title: MemoryCacheAccessor.Clear Method  (Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache)
TOCTitle: Clear Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.Clear(Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cache.memorycache.memorycacheaccessor.clear(v=AX.60)
ms:contentKeyID: 65320674
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.Clear
dev_langs:
- CSharp
- C++
- VB
---

# Clear Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Clears all the entities for the given data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.dll)

## Syntax

``` vb
'Declaration
Public Sub Clear ( _
    currentStore As IDataStore _
)
'Usage
Dim instance As MemoryCacheAccessor
Dim currentStore As IDataStore

instance.Clear(currentStore)
```

``` csharp
public void Clear(
    IDataStore currentStore
)
```

``` c++
public:
virtual void Clear(
    IDataStore^ currentStore
) sealed
```

#### Parameters

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[IKeyedDataStoreAccessor.Clear(IDataStore)](ikeyeddatastoreaccessor-clear-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[MemoryCacheAccessor Class](memorycacheaccessor-class-microsoft-dynamics-commerce-runtime-cache-memorycache.md)

[Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache Namespace](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)

