---
title: UpdateListingPublishingStatusRequest.StatusList Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StatusList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateListingPublishingStatusRequest.StatusList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.updatelistingpublishingstatusrequest.statuslist(v=AX.60)
ms:contentKeyID: 49846078
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateListingPublishingStatusRequest.StatusList
dev_langs:
- CSharp
- C++
- VB
---

# StatusList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the status list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StatusList As IEnumerable(Of ListingPublishStatus)
    Get
    Set
'Usage
Dim instance As UpdateListingPublishingStatusRequest
Dim value As IEnumerable(Of ListingPublishStatus)

value = instance.StatusList

instance.StatusList = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ListingPublishStatus> StatusList { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ListingPublishStatus^>^ StatusList {
    IEnumerable<ListingPublishStatus^>^ get ();
    void set (IEnumerable<ListingPublishStatus^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ListingPublishStatus](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The status list.  

## See Also

#### Reference

[UpdateListingPublishingStatusRequest Class](updatelistingpublishingstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

