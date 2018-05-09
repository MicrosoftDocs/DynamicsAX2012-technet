---
title: ProductL2CacheDataStoreAccessor.PutIdsOfChangedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutIdsOfChangedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutIdsOfChangedProducts(System.Guid,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityChangeTrackingInformation})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.putidsofchangedproducts(v=AX.60)
ms:contentKeyID: 62208904
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutIdsOfChangedProducts
dev_langs:
- CSharp
- C++
- VB
---

# PutIdsOfChangedProducts Method

Saves IDS of changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutIdsOfChangedProducts ( _
    sessionId As Guid, _
    productIds As ReadOnlyCollection(Of CommerceEntityChangeTrackingInformation) _
)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim sessionId As Guid
Dim productIds As ReadOnlyCollection(Of CommerceEntityChangeTrackingInformation)

instance.PutIdsOfChangedProducts(sessionId, _
    productIds)
```

``` csharp
public void PutIdsOfChangedProducts(
    Guid sessionId,
    ReadOnlyCollection<CommerceEntityChangeTrackingInformation> productIds
)
```

``` c++
public:
void PutIdsOfChangedProducts(
    Guid sessionId, 
    ReadOnlyCollection<CommerceEntityChangeTrackingInformation^>^ productIds
)
```

#### Parameters

  - sessionId  
    Type: [System.Guid](https://technet.microsoft.com/en-us/library/cey1zx63\(v=ax.60\))  

<!-- end list -->

  - productIds  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CommerceEntityChangeTrackingInformation](commerceentitychangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

