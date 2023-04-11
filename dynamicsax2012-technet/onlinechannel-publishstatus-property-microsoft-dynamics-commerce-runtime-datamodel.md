---
title: OnlineChannel.PublishStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PublishStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel.PublishStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.onlinechannel.publishstatus(v=AX.60)
ms:contentKeyID: 49840717
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel.PublishStatus
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the publishing status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PUBLISHSTATUS")> _
<DataMemberAttribute> _
Public Property PublishStatus As OnlineChannelPublishStatusType
    Get
    Friend Set
'Usage
Dim instance As OnlineChannel
Dim value As OnlineChannelPublishStatusType

value = instance.PublishStatus
```

``` csharp
[ColumnAttribute("PUBLISHSTATUS")]
[DataMemberAttribute]
public OnlineChannelPublishStatusType PublishStatus { get; internal set; }
```

``` c++
[ColumnAttribute(L"PUBLISHSTATUS")]
[DataMemberAttribute]
public:
property OnlineChannelPublishStatusType PublishStatus {
    OnlineChannelPublishStatusType get ();
    internal: void set (OnlineChannelPublishStatusType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [OnlineChannelPublishStatusType](onlinechannelpublishstatustype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OnlineChannel Class](onlinechannel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

