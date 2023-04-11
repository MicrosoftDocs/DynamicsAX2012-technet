---
title: MemoryCacheAccessor.InitializeDataStores Method  (Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache)
TOCTitle: InitializeDataStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.InitializeDataStores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cache.memorycache.memorycacheaccessor.initializedatastores(v=AX.60)
ms:contentKeyID: 65322423
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.MemoryCacheAccessor.InitializeDataStores
dev_langs:
- CSharp
- C++
- VB
---

# InitializeDataStores Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes the static object that is the data store manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache.dll)

## Syntax

``` vb
'Declaration
Public Function InitializeDataStores As Lazy(Of Dictionary(Of DataStoreType, IDataStore))
'Usage
Dim instance As MemoryCacheAccessor
Dim returnValue As Lazy(Of Dictionary(Of DataStoreType, IDataStore))

returnValue = instance.InitializeDataStores()
```

``` csharp
public Lazy<Dictionary<DataStoreType, IDataStore>> InitializeDataStores()
```

``` c++
public:
virtual Lazy<Dictionary<DataStoreType, IDataStore^>^>^ InitializeDataStores() sealed
```

#### Return Value

Type: Lazy\<[Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md), [IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)\>\>  
An instance of the data store manager object.  

#### Implements

[IKeyedDataStoreAccessor.InitializeDataStores()](ikeyeddatastoreaccessor-initializedatastores-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[MemoryCacheAccessor Class](memorycacheaccessor-class-microsoft-dynamics-commerce-runtime-cache-memorycache.md)

[Microsoft.Dynamics.Commerce.Runtime.Cache.MemoryCache Namespace](microsoft-dynamics-commerce-runtime-cache-memorycache-namespace.md)

