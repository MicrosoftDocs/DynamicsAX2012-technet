---
title: GetNextBatchListingPublishStatusesRequest.ActionStatus Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ActionStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetNextBatchListingPublishStatusesRequest.ActionStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getnextbatchlistingpublishstatusesrequest.actionstatus(v=AX.60)
ms:contentKeyID: 62214624
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetNextBatchListingPublishStatusesRequest.ActionStatus
dev_langs:
- CSharp
- C++
- VB
---

# ActionStatus Property

Gets or sets the action status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActionStatus As ListingPublishingActionStatus
    Get
    Set
'Usage
Dim instance As GetNextBatchListingPublishStatusesRequest
Dim value As ListingPublishingActionStatus

value = instance.ActionStatus

instance.ActionStatus = value
```

``` csharp
[DataMemberAttribute]
public ListingPublishingActionStatus ActionStatus { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ListingPublishingActionStatus ActionStatus {
    ListingPublishingActionStatus get ();
    void set (ListingPublishingActionStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishingActionStatus](listingpublishingactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The action status.  

## See Also

#### Reference

[GetNextBatchListingPublishStatusesRequest Class](getnextbatchlistingpublishstatusesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

