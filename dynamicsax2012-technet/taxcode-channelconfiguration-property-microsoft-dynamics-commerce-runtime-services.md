---
title: TaxCode.ChannelConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: ChannelConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.ChannelConfiguration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.taxcode.channelconfiguration(v=AX.60)
ms:contentKeyID: 49831737
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.ChannelConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ChannelConfiguration Property

Gets the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Property ChannelConfiguration As ChannelConfiguration
    Get
    Private Set
'Usage
Dim value As ChannelConfiguration

value = Me.ChannelConfiguration
```

``` csharp
protected ChannelConfiguration ChannelConfiguration { get; private set; }
```

``` c++
protected:
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

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

