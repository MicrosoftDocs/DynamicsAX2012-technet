---
title: Publisher.PublishChannel Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: PublishChannel Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher.PublishChannel(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.IChannelPublisher)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.publisher.publishchannel(v=AX.60)
ms:contentKeyID: 65316190
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher.PublishChannel
dev_langs:
- CSharp
- C++
- VB
---

# PublishChannel Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Function PublishChannel ( _
    channelPublisher As IChannelPublisher _
) As PublishingParameters
'Usage
Dim instance As Publisher
Dim channelPublisher As IChannelPublisher
Dim returnValue As PublishingParameters

returnValue = instance.PublishChannel(channelPublisher)
```

``` csharp
public PublishingParameters PublishChannel(
    IChannelPublisher channelPublisher
)
```

``` c++
public:
PublishingParameters^ PublishChannel(
    IChannelPublisher^ channelPublisher
)
```

#### Parameters

  - channelPublisher  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.IChannelPublisher](ichannelpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters](publishingparameters-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)  

## See Also

#### Reference

[Publisher Class](publisher-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

