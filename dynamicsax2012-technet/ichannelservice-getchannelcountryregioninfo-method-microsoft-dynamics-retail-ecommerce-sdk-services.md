---
title: IChannelService.GetChannelCountryRegionInfo Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetChannelCountryRegionInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IChannelService.GetChannelCountryRegionInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.ichannelservice.getchannelcountryregioninfo(v=AX.60)
ms:contentKeyID: 65318187
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IChannelService.GetChannelCountryRegionInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCountryRegionInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetChannelCountryRegionInfo As CountryInfoResponse
'Usage
Dim instance As IChannelService
Dim returnValue As CountryInfoResponse

returnValue = instance.GetChannelCountryRegionInfo()
```

``` csharp
[OperationContractAttribute]
CountryInfoResponse GetChannelCountryRegionInfo()
```

``` c++
[OperationContractAttribute]
CountryInfoResponse^ GetChannelCountryRegionInfo()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CountryInfoResponse](countryinforesponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IChannelService Interface](ichannelservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

