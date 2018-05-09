---
title: GetOnlineChannelResponse.Channel Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Channel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOnlineChannelResponse.Channel
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getonlinechannelresponse.channel(v=AX.60)
ms:contentKeyID: 49818976
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOnlineChannelResponse.Channel
dev_langs:
- CSharp
- C++
- VB
---

# Channel Property

Gets the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Channel As OnlineChannel
    Get
    Private Set
'Usage
Dim instance As GetOnlineChannelResponse
Dim value As OnlineChannel

value = instance.Channel
```

``` csharp
[DataMemberAttribute]
public OnlineChannel Channel { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property OnlineChannel^ Channel {
    OnlineChannel^ get ();
    private: void set (OnlineChannel^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel](onlinechannel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [OnlineChannel](onlinechannel-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetOnlineChannelResponse Class](getonlinechannelresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

