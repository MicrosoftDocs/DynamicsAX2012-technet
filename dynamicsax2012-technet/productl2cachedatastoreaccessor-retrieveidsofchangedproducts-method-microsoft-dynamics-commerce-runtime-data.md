---
title: ProductL2CacheDataStoreAccessor.RetrieveIdsOfChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: RetrieveIdsOfChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.RetrieveIdsOfChangedProducts(System.Guid)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.retrieveidsofchangedproducts(v=AX.60)
ms:contentKeyID: 62204343
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.RetrieveIdsOfChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# RetrieveIdsOfChangedProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrievs IDs of changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function RetrieveIdsOfChangedProducts ( _
    sessionId As Guid _
) As ReadOnlyCollection(Of CommerceEntityChangeTrackingInformation)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim sessionId As Guid
Dim returnValue As ReadOnlyCollection(Of CommerceEntityChangeTrackingInformation)

returnValue = instance.RetrieveIdsOfChangedProducts(sessionId)
```

``` csharp
public ReadOnlyCollection<CommerceEntityChangeTrackingInformation> RetrieveIdsOfChangedProducts(
    Guid sessionId
)
```

``` c++
public:
ReadOnlyCollection<CommerceEntityChangeTrackingInformation^>^ RetrieveIdsOfChangedProducts(
    Guid sessionId
)
```

#### Parameters

  - sessionId  
    Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CommerceEntityChangeTrackingInformation](commerceentitychangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of changed product's IDs.  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

