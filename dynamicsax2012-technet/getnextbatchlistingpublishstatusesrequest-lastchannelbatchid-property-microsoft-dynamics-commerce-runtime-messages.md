---
title: GetNextBatchListingPublishStatusesRequest.LastChannelBatchId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LastChannelBatchId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetNextBatchListingPublishStatusesRequest.LastChannelBatchId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getnextbatchlistingpublishstatusesrequest.lastchannelbatchid(v=AX.60)
ms:contentKeyID: 62209455
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetNextBatchListingPublishStatusesRequest.LastChannelBatchId
dev_langs:
- CSharp
- C++
- VB
---

# LastChannelBatchId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the last channel batch identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LastChannelBatchId As String
    Get
    Set
'Usage
Dim instance As GetNextBatchListingPublishStatusesRequest
Dim value As String

value = instance.LastChannelBatchId

instance.LastChannelBatchId = value
```

``` csharp
[DataMemberAttribute]
public string LastChannelBatchId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LastChannelBatchId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The last channel batch identifier.  

## See Also

#### Reference

[GetNextBatchListingPublishStatusesRequest Class](getnextbatchlistingpublishstatusesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

