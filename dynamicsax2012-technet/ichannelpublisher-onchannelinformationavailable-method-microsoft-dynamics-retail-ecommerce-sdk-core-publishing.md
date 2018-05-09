---
title: IChannelPublisher.OnChannelInformationAvailable Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: OnChannelInformationAvailable Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.IChannelPublisher.OnChannelInformationAvailable(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.ichannelpublisher.onchannelinformationavailable(v=AX.60)
ms:contentKeyID: 65316907
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.IChannelPublisher.OnChannelInformationAvailable
dev_langs:
- CSharp
- C++
- VB
---

# OnChannelInformationAvailable Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Sub OnChannelInformationAvailable ( _
    parameters As PublishingParameters, _
    isPublishingRequested As Boolean _
)
'Usage
Dim instance As IChannelPublisher
Dim parameters As PublishingParameters
Dim isPublishingRequested As Boolean

instance.OnChannelInformationAvailable(parameters, _
    isPublishingRequested)
```

``` csharp
void OnChannelInformationAvailable(
    PublishingParameters parameters,
    bool isPublishingRequested
)
```

``` c++
void OnChannelInformationAvailable(
    PublishingParameters^ parameters, 
    bool isPublishingRequested
)
```

#### Parameters

  - parameters  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters](publishingparameters-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)  

<!-- end list -->

  - isPublishingRequested  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IChannelPublisher Interface](ichannelpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

