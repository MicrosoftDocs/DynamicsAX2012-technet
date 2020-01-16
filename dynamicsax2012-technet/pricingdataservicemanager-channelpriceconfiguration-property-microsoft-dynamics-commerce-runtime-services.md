---
title: PricingDataServiceManager.ChannelPriceConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: ChannelPriceConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.ChannelPriceConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.channelpriceconfiguration(v=AX.60)
ms:contentKeyID: 65318934
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.ChannelPriceConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ChannelPriceConfiguration Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property ChannelPriceConfiguration As ChannelPriceConfiguration
    Get
'Usage
Dim instance As PricingDataServiceManager
Dim value As ChannelPriceConfiguration

value = instance.ChannelPriceConfiguration
```

``` csharp
public ChannelPriceConfiguration ChannelPriceConfiguration { get; }
```

``` c++
public:
virtual property ChannelPriceConfiguration^ ChannelPriceConfiguration {
    ChannelPriceConfiguration^ get () sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelPriceConfiguration](channelpriceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[IPricingDataManagerV2.ChannelPriceConfiguration](ipricingdatamanagerv2-channelpriceconfiguration-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

