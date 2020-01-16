---
title: DataCacheAccessor.CacheAccessor Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CacheAccessor Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CacheAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor.cacheaccessor(v=AX.60)
ms:contentKeyID: 65322359
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CacheAccessor
dev_langs:
- CSharp
- C++
- VB
---

# CacheAccessor Property

Gets or sets interface for cache data store, use the interface methods to access the data store (get, put and evict methods).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Property CacheAccessor As IKeyedDataStoreAccessor
    Get
    Set
'Usage
Dim value As IKeyedDataStoreAccessor

value = Me.CacheAccessor

Me.CacheAccessor = value
```

``` csharp
protected IKeyedDataStoreAccessor CacheAccessor { get; set; }
```

``` c++
protected:
property IKeyedDataStoreAccessor^ CacheAccessor {
    IKeyedDataStoreAccessor^ get ();
    void set (IKeyedDataStoreAccessor^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md)  
Returns [IKeyedDataStoreAccessor](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

