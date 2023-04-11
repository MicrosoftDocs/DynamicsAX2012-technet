---
title: Listing.CreateStatusFailedToPublish Method  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: CreateStatusFailedToPublish Method
ms:assetid: M:Microsoft.Dynamics.Retail.Channels.Listing.CreateStatusFailedToPublish(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.createstatusfailedtopublish(v=AX.60)
ms:contentKeyID: 65318218
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.CreateStatusFailedToPublish
dev_langs:
- CSharp
- C++
- VB
---

# CreateStatusFailedToPublish Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Function CreateStatusFailedToPublish ( _
    statusMessage As String _
) As ListingPublishStatus
'Usage
Dim instance As Listing
Dim statusMessage As String
Dim returnValue As ListingPublishStatus

returnValue = instance.CreateStatusFailedToPublish(statusMessage)
```

``` csharp
public ListingPublishStatus CreateStatusFailedToPublish(
    string statusMessage
)
```

``` c++
public:
ListingPublishStatus^ CreateStatusFailedToPublish(
    String^ statusMessage
)
```

#### Parameters

  - statusMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: ListingPublishStatus  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

