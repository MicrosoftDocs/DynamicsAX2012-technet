---
title: TaxL2CacheDataStoreAccessor Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TaxL2CacheDataStoreAccessor Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.taxl2cachedatastoreaccessor(v=AX.60)
ms:contentKeyID: 65321959
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# TaxL2CacheDataStoreAccessor Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    backingStore As IDataStore, _
    context As RequestContext _
)
'Usage
Dim backingStore As IDataStore
Dim context As RequestContext

Dim instance As New TaxL2CacheDataStoreAccessor(backingStore, _
    context)
```

``` csharp
protected TaxL2CacheDataStoreAccessor(
    IDataStore backingStore,
    RequestContext context
)
```

``` c++
protected:
TaxL2CacheDataStoreAccessor(
    IDataStore^ backingStore, 
    RequestContext^ context
)
```

#### Parameters

  - backingStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

