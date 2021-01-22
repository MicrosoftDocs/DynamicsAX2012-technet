---
title: ChannelInfoResponse.ChannelConfiguration Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ChannelConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ChannelInfoResponse.ChannelConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.channelinforesponse.channelconfiguration(v=AX.60)
ms:contentKeyID: 65318410
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ChannelInfoResponse.ChannelConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ChannelConfiguration Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelConfiguration As ChannelConfiguration
    Get
    Set
'Usage
Dim instance As ChannelInfoResponse
Dim value As ChannelConfiguration

value = instance.ChannelConfiguration

instance.ChannelConfiguration = value
```

``` csharp
[DataMemberAttribute]
public ChannelConfiguration ChannelConfiguration { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ChannelConfiguration^ ChannelConfiguration {
    ChannelConfiguration^ get ();
    void set (ChannelConfiguration^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[ChannelInfoResponse Class](channelinforesponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

