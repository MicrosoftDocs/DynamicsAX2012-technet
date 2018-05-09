---
title: DataCacheAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataCacheAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor(v=AX.60)
ms:contentKeyID: 65321099
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor
dev_langs:
- CSharp
- C++
- VB
---

# DataCacheAccessor Class

Class modeling the behavior of a memory cache accessor.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class DataCacheAccessor _
    Inherits DataStoreAccessor
'Usage
Dim instance As DataCacheAccessor
```

``` csharp
public abstract class DataCacheAccessor : DataStoreAccessor
```

``` c++
public ref class DataCacheAccessor abstract : public DataStoreAccessor
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor](chargel2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor](currencyl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.L2CacheDataStoreAccessor](l2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

