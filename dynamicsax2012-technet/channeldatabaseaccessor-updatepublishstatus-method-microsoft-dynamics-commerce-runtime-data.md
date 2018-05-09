---
title: ChannelDatabaseAccessor.UpdatePublishStatus Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: UpdatePublishStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.UpdatePublishStatus(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.updatepublishstatus(v=AX.60)
ms:contentKeyID: 62207976
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.UpdatePublishStatus
dev_langs:
- CSharp
- C++
- VB
---

# UpdatePublishStatus Method

Updates the publishing status of the channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function UpdatePublishStatus ( _
    channelId As Long, _
    publishStatus As OnlineChannelPublishStatusType, _
    publishStatusMessage As String _
) As Boolean
'Usage
Dim instance As ChannelDatabaseAccessor
Dim channelId As Long
Dim publishStatus As OnlineChannelPublishStatusType
Dim publishStatusMessage As String
Dim returnValue As Boolean

returnValue = instance.UpdatePublishStatus(channelId, _
    publishStatus, publishStatusMessage)
```

``` csharp
public bool UpdatePublishStatus(
    long channelId,
    OnlineChannelPublishStatusType publishStatus,
    string publishStatusMessage
)
```

``` c++
public:
bool UpdatePublishStatus(
    long long channelId, 
    OnlineChannelPublishStatusType publishStatus, 
    String^ publishStatusMessage
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - publishStatus  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - publishStatusMessage  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Result that indicates whether the update is successful.  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

