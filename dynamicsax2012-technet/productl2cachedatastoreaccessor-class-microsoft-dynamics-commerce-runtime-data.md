---
title: ProductL2CacheDataStoreAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ProductL2CacheDataStoreAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor(v=AX.60)
ms:contentKeyID: 62215193
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor
dev_langs:
- CSharp
- C++
- VB
---

# ProductL2CacheDataStoreAccessor Class

Represents a database accessor, specialized in retrieving listing information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ProductL2CacheDataStoreAccessor _
    Inherits DataCacheAccessor _
    Implements ICachedProductDataManager
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
```

``` csharp
public sealed class ProductL2CacheDataStoreAccessor : DataCacheAccessor, 
    ICachedProductDataManager
```

``` c++
public ref class ProductL2CacheDataStoreAccessor sealed : public DataCacheAccessor, 
    ICachedProductDataManager
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

