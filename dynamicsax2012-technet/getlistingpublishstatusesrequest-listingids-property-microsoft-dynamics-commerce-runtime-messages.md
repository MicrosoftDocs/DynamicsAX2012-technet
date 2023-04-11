---
title: GetListingPublishStatusesRequest.ListingIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ListingIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingPublishStatusesRequest.ListingIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlistingpublishstatusesrequest.listingids(v=AX.60)
ms:contentKeyID: 62208184
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingPublishStatusesRequest.ListingIds
dev_langs:
- CSharp
- C++
- VB
---

# ListingIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the listing identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ListingIds As IEnumerable(Of Long)
    Get
    Set
'Usage
Dim instance As GetListingPublishStatusesRequest
Dim value As IEnumerable(Of Long)

value = instance.ListingIds

instance.ListingIds = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<long> ListingIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<long long>^ ListingIds {
    IEnumerable<long long>^ get ();
    void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
The listing identifiers.  

## See Also

#### Reference

[GetListingPublishStatusesRequest Class](getlistingpublishstatusesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

