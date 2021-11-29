---
title: ICatalogPublisher.OnDeleteIndividualProductsRequested Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: OnDeleteIndividualProductsRequested Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnDeleteIndividualProductsRequested(System.Collections.Generic.IList{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ListingIdentity})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.icatalogpublisher.ondeleteindividualproductsrequested(v=AX.60)
ms:contentKeyID: 65316326
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnDeleteIndividualProductsRequested
dev_langs:
- CSharp
- C++
- VB
---

# OnDeleteIndividualProductsRequested Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Sub OnDeleteIndividualProductsRequested ( _
    ids As IList(Of ListingIdentity) _
)
'Usage
Dim instance As ICatalogPublisher
Dim ids As IList(Of ListingIdentity)

instance.OnDeleteIndividualProductsRequested(ids)
```

``` csharp
void OnDeleteIndividualProductsRequested(
    IList<ListingIdentity> ids
)
```

``` c++
void OnDeleteIndividualProductsRequested(
    IList<ListingIdentity^>^ ids
)
```

#### Parameters

  - ids  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ListingIdentity](listingidentity-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)\>  

## See Also

#### Reference

[ICatalogPublisher Interface](icatalogpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

