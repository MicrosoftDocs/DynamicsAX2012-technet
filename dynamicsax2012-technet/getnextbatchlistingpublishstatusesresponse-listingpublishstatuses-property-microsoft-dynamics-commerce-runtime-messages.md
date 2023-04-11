---
title: GetNextBatchListingPublishStatusesResponse.ListingPublishStatuses Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ListingPublishStatuses Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetNextBatchListingPublishStatusesResponse.ListingPublishStatuses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getnextbatchlistingpublishstatusesresponse.listingpublishstatuses(v=AX.60)
ms:contentKeyID: 62210377
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetNextBatchListingPublishStatusesResponse.ListingPublishStatuses
dev_langs:
- CSharp
- C++
- VB
---

# ListingPublishStatuses Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the listingPublishStatuses.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingPublishStatuses As ReadOnlyCollection(Of ListingPublishStatus)
    Get
    Private Set
'Usage
Dim instance As GetNextBatchListingPublishStatusesResponse
Dim value As ReadOnlyCollection(Of ListingPublishStatus)

value = instance.ListingPublishStatuses
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ListingPublishStatus> ListingPublishStatuses { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ListingPublishStatus^>^ ListingPublishStatuses {
    ReadOnlyCollection<ListingPublishStatus^>^ get ();
    private: void set (ReadOnlyCollection<ListingPublishStatus^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ListingPublishStatus](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetNextBatchListingPublishStatusesResponse Class](getnextbatchlistingpublishstatusesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

