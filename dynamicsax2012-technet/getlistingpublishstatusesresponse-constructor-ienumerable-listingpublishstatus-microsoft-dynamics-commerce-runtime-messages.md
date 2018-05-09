---
title: GetListingPublishStatusesResponse Constructor (IEnumerable(ListingPublishStatus)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetListingPublishStatusesResponse Constructor (IEnumerable(ListingPublishStatus))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingPublishStatusesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getlistingpublishstatusesresponse.getlistingpublishstatusesresponse(v=AX.60)
ms:contentKeyID: 62209227
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetListingPublishStatusesResponse Constructor (IEnumerable(ListingPublishStatus))

Initializes a new instance of the [GetListingPublishStatusesResponse](getlistingpublishstatusesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

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

Dim instance As New GetListingPublishStatusesResponse(listingPublishStatuses)
```

``` csharp
public GetListingPublishStatusesResponse(
    IEnumerable<ListingPublishStatus> listingPublishStatuses
)
```

``` c++
public:
GetListingPublishStatusesResponse(
    IEnumerable<ListingPublishStatus^>^ listingPublishStatuses
)
```

#### Parameters

  - listingPublishStatuses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ListingPublishStatus](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetListingPublishStatusesResponse Class](getlistingpublishstatusesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetListingPublishStatusesResponse Overload](getlistingpublishstatusesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

