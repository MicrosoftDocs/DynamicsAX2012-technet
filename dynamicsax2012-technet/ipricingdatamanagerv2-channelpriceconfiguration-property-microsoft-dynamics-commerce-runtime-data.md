---
title: IPricingDataManagerV2.ChannelPriceConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ChannelPriceConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.ChannelPriceConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.channelpriceconfiguration(v=AX.60)
ms:contentKeyID: 62203528
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.ChannelPriceConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ChannelPriceConfiguration Property

Gets channel price configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ChannelPriceConfiguration As ChannelPriceConfiguration
    Get
'Usage
Dim instance As IPricingDataManagerV2
Dim value As ChannelPriceConfiguration

value = instance.ChannelPriceConfiguration
```

``` csharp
ChannelPriceConfiguration ChannelPriceConfiguration { get; }
```

``` c++
property ChannelPriceConfiguration^ ChannelPriceConfiguration {
    ChannelPriceConfiguration^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelPriceConfiguration](channelpriceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChannelPriceConfiguration](channelpriceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

