---
title: PricingDataManager.ChannelPriceConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ChannelPriceConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.ChannelPriceConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.channelpriceconfiguration(v=AX.60)
ms:contentKeyID: 62210363
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.ChannelPriceConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ChannelPriceConfiguration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets channel price configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property ChannelPriceConfiguration As ChannelPriceConfiguration
    Get
'Usage
Dim instance As PricingDataManager
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
Returns [ChannelPriceConfiguration](channelpriceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

#### Implements

[IPricingDataManagerV2.ChannelPriceConfiguration](ipricingdatamanagerv2-channelpriceconfiguration-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

