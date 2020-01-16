---
title: GetNextBatchListingPublishStatusesResponse Constructor (IEnumerable(ListingPublishStatus)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetNextBatchListingPublishStatusesResponse Constructor (IEnumerable(ListingPublishStatus))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetNextBatchListingPublishStatusesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getnextbatchlistingpublishstatusesresponse.getnextbatchlistingpublishstatusesresponse(v=AX.60)
ms:contentKeyID: 62205132
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetNextBatchListingPublishStatusesResponse Constructor (IEnumerable(ListingPublishStatus))

Initializes a new instance of the [GetNextBatchListingPublishStatusesResponse](getnextbatchlistingpublishstatusesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    listingPublishStatuses As IEnumerable(Of ListingPublishStatus) _
)
'Usage
Dim listingPublishStatuses As IEnumerable(Of ListingPublishStatus)

Dim instance As New GetNextBatchListingPublishStatusesResponse(listingPublishStatuses)
```

``` csharp
public GetNextBatchListingPublishStatusesResponse(
    IEnumerable<ListingPublishStatus> listingPublishStatuses
)
```

``` c++
public:
GetNextBatchListingPublishStatusesResponse(
    IEnumerable<ListingPublishStatus^>^ listingPublishStatuses
)
```

#### Parameters

  - listingPublishStatuses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingPublishStatus](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetNextBatchListingPublishStatusesResponse Class](getnextbatchlistingpublishstatusesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetNextBatchListingPublishStatusesResponse Overload](getnextbatchlistingpublishstatusesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

