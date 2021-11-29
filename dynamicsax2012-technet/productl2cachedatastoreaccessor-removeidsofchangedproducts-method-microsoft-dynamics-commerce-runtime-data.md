---
title: ProductL2CacheDataStoreAccessor.RemoveIdsOfChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: RemoveIdsOfChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.RemoveIdsOfChangedProducts(System.Guid)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.removeidsofchangedproducts(v=AX.60)
ms:contentKeyID: 62210887
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.RemoveIdsOfChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# RemoveIdsOfChangedProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Removes changed product's IDs from cache.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub RemoveIdsOfChangedProducts ( _
    sessionId As Guid _
)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim sessionId As Guid

instance.RemoveIdsOfChangedProducts(sessionId)
```

``` csharp
public void RemoveIdsOfChangedProducts(
    Guid sessionId
)
```

``` c++
public:
void RemoveIdsOfChangedProducts(
    Guid sessionId
)
```

#### Parameters

  - sessionId  
    Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

