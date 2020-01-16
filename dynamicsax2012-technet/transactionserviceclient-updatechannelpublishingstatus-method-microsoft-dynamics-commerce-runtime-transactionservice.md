---
title: TransactionServiceClient.UpdateChannelPublishingStatus Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: UpdateChannelPublishingStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateChannelPublishingStatus(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.updatechannelpublishingstatus(v=AX.60)
ms:contentKeyID: 49850329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateChannelPublishingStatus
dev_langs:
- CSharp
- C++
- VB
---

# UpdateChannelPublishingStatus Method

Updates the publishing status and message for the given channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateChannelPublishingStatus ( _
    channelId As Long, _
    publishingStatus As OnlineChannelPublishStatusType, _
    publishingStatusMessage As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim channelId As Long
Dim publishingStatus As OnlineChannelPublishStatusType
Dim publishingStatusMessage As String

instance.UpdateChannelPublishingStatus(channelId, _
    publishingStatus, publishingStatusMessage)
```

``` csharp
public void UpdateChannelPublishingStatus(
    long channelId,
    OnlineChannelPublishStatusType publishingStatus,
    string publishingStatusMessage
)
```

``` c++
public:
void UpdateChannelPublishingStatus(
    long long channelId, 
    OnlineChannelPublishStatusType publishingStatus, 
    String^ publishingStatusMessage
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - publishingStatus  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - publishingStatusMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

