---
title: DataAccessor.DeleteListingsByCompositeIds Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: DeleteListingsByCompositeIds Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.DataAccessor.DeleteListingsByCompositeIds(System.Int64,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ListingIdentity})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.dataaccessor.deletelistingsbycompositeids(v=AX.60)
ms:contentKeyID: 65316200
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.DataAccessor.DeleteListingsByCompositeIds
dev_langs:
- CSharp
- C++
- VB
---

# DeleteListingsByCompositeIds Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Sub DeleteListingsByCompositeIds ( _
    catalogId As Long, _
    ids As IEnumerable(Of ListingIdentity) _
)
'Usage
Dim instance As DataAccessor
Dim catalogId As Long
Dim ids As IEnumerable(Of ListingIdentity)

instance.DeleteListingsByCompositeIds(catalogId, _
    ids)
```

``` csharp
public void DeleteListingsByCompositeIds(
    long catalogId,
    IEnumerable<ListingIdentity> ids
)
```

``` c++
public:
void DeleteListingsByCompositeIds(
    long long catalogId, 
    IEnumerable<ListingIdentity^>^ ids
)
```

#### Parameters

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - ids  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ListingIdentity](listingidentity-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)\>  

## See Also

#### Reference

[DataAccessor Class](dataaccessor-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

