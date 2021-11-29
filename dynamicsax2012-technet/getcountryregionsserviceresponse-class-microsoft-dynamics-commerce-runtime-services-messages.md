---
title: GetCountryRegionsServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCountryRegionsServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountryRegionsServiceResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcountryregionsserviceresponse(v=AX.60)
ms:contentKeyID: 62214586
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountryRegionsServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetCountryRegionsServiceResponse Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the response for the [GetCountryRegionsServiceRequest](getcountryregionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetCountryRegionsServiceResponse _
    Inherits GetAddressInfoServiceResponse(Of CountryRegionInfo)
'Usage
Dim instance As GetCountryRegionsServiceResponse
```

``` csharp
[DataContractAttribute]
public class GetCountryRegionsServiceResponse : GetAddressInfoServiceResponse<CountryRegionInfo>
```

``` c++
[DataContractAttribute]
public ref class GetCountryRegionsServiceResponse : public GetAddressInfoServiceResponse<CountryRegionInfo^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\<[CountryRegionInfo](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountryRegionsServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

