---
title: Services.ChannelServiceUrl Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: ChannelServiceUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.ChannelServiceUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.services.channelserviceurl(v=AX.60)
ms:contentKeyID: 65317801
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.ChannelServiceUrl
dev_langs:
- CSharp
- C++
- VB
---

# ChannelServiceUrl Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("channelServiceUrl")> _
Public ReadOnly Property ChannelServiceUrl As String
    Get
'Usage
Dim instance As Services
Dim value As String

value = instance.ChannelServiceUrl
```

``` csharp
[ConfigurationPropertyAttribute("channelServiceUrl")]
public string ChannelServiceUrl { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"channelServiceUrl")]
public:
property String^ ChannelServiceUrl {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Services Class](services-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

