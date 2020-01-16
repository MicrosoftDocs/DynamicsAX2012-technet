---
title: TaxL2CacheDataStoreAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TaxL2CacheDataStoreAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor(v=AX.60)
ms:contentKeyID: 62209673
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor
dev_langs:
- CSharp
- C++
- VB
---

# TaxL2CacheDataStoreAccessor Class

Level 2 cache data accessor implementation for the tax data manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Class TaxL2CacheDataStoreAccessor _
    Inherits DataCacheAccessor _
    Implements ICachedTaxDataManager, ITaxDataManager
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
```

``` csharp
public class TaxL2CacheDataStoreAccessor : DataCacheAccessor, 
    ICachedTaxDataManager, ITaxDataManager
```

``` c++
public ref class TaxL2CacheDataStoreAccessor : public DataCacheAccessor, 
    ICachedTaxDataManager, ITaxDataManager
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

