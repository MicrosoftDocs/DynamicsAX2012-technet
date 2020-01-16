---
title: SaveCustomerOrderServiceRequest.ChannelConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ChannelConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest.ChannelConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecustomerorderservicerequest.channelconfiguration(v=AX.60)
ms:contentKeyID: 62209016
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest.ChannelConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ChannelConfiguration Property

Gets or sets the channel configuration for current channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property ChannelConfiguration As ChannelConfiguration
    Get
    Set
'Usage
Dim instance As SaveCustomerOrderServiceRequest
Dim value As ChannelConfiguration

value = instance.ChannelConfiguration

instance.ChannelConfiguration = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ChannelConfiguration ChannelConfiguration { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ChannelConfiguration^ ChannelConfiguration {
    ChannelConfiguration^ get ();
    void set (ChannelConfiguration^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveCustomerOrderServiceRequest Class](savecustomerorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

