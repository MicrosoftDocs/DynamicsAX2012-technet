---
title: Publisher Constructor  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: Publisher Constructor
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher.#ctor(System.Configuration.Configuration,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingConfiguration)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.publisher.publisher(v=AX.60)
ms:contentKeyID: 65318183
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# Publisher Constructor

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    appConfig As Configuration, _
    publishingConfig As PublishingConfiguration _
)
'Usage
Dim appConfig As Configuration
Dim publishingConfig As PublishingConfiguration

Dim instance As New Publisher(appConfig, _
    publishingConfig)
```

``` csharp
public Publisher(
    Configuration appConfig,
    PublishingConfiguration publishingConfig
)
```

``` c++
public:
Publisher(
    Configuration^ appConfig, 
    PublishingConfiguration^ publishingConfig
)
```

#### Parameters

  - appConfig  
    Type: [System.Configuration.Configuration](https://technet.microsoft.com/library/s7kc101z\(v=ax.60\))  

<!-- end list -->

  - publishingConfig  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingConfiguration](publishingconfiguration-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)  

## See Also

#### Reference

[Publisher Class](publisher-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

