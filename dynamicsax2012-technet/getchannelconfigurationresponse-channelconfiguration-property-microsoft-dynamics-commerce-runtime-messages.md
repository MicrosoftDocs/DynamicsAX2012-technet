---
title: GetChannelConfigurationResponse.ChannelConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelConfigurationResponse.ChannelConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelconfigurationresponse.channelconfiguration(v=AX.60)
ms:contentKeyID: 62208581
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelConfigurationResponse.ChannelConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ChannelConfiguration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelConfiguration As ChannelConfiguration
    Get
    Private Set
'Usage
Dim instance As GetChannelConfigurationResponse
Dim value As ChannelConfiguration

value = instance.ChannelConfiguration
```

``` csharp
[DataMemberAttribute]
public ChannelConfiguration ChannelConfiguration { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ChannelConfiguration^ ChannelConfiguration {
    ChannelConfiguration^ get ();
    private: void set (ChannelConfiguration^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetChannelConfigurationResponse Class](getchannelconfigurationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

