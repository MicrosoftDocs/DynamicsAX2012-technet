---
title: ProductManager.UpdateListingPublishingStatus Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateListingPublishingStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.UpdateListingPublishingStatus(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.updatelistingpublishingstatus(v=AX.60)
ms:contentKeyID: 49855972
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.UpdateListingPublishingStatus
dev_langs:
- CSharp
- C++
- VB
---

# UpdateListingPublishingStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Applies the specified list of publishing statuses.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateListingPublishingStatus ( _
    publishingStatuses As IEnumerable(Of ListingPublishStatus) _
)
'Usage
Dim instance As ProductManager
Dim publishingStatuses As IEnumerable(Of ListingPublishStatus)

instance.UpdateListingPublishingStatus(publishingStatuses)
```

``` csharp
public void UpdateListingPublishingStatus(
    IEnumerable<ListingPublishStatus> publishingStatuses
)
```

``` c++
public:
void UpdateListingPublishingStatus(
    IEnumerable<ListingPublishStatus^>^ publishingStatuses
)
```

#### Parameters

  - publishingStatuses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingPublishStatus](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

