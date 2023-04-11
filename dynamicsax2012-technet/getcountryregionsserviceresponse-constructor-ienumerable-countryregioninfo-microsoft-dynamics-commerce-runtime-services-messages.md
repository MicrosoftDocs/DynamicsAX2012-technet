---
title: GetCountryRegionsServiceResponse Constructor (IEnumerable(CountryRegionInfo)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCountryRegionsServiceResponse Constructor (IEnumerable(CountryRegionInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountryRegionsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcountryregionsserviceresponse.getcountryregionsserviceresponse(v=AX.60)
ms:contentKeyID: 62214180
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCountryRegionsServiceResponse Constructor (IEnumerable(CountryRegionInfo))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCountryRegionsServiceResponse](getcountryregionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countries As IEnumerable(Of CountryRegionInfo) _
)
'Usage
Dim countries As IEnumerable(Of CountryRegionInfo)

Dim instance As New GetCountryRegionsServiceResponse(countries)
```

``` csharp
public GetCountryRegionsServiceResponse(
    IEnumerable<CountryRegionInfo> countries
)
```

``` c++
public:
GetCountryRegionsServiceResponse(
    IEnumerable<CountryRegionInfo^>^ countries
)
```

#### Parameters

  - countries  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CountryRegionInfo](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCountryRegionsServiceResponse Class](getcountryregionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCountryRegionsServiceResponse Overload](getcountryregionsserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

