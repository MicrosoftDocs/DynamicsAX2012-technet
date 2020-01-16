---
title: GetCountryRegionDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetCountryRegionDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountryRegionDataResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcountryregiondataresponse.getcountryregiondataresponse(v=AX.60)
ms:contentKeyID: 65320125
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountryRegionDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetCountryRegionDataResponse Constructor

Initializes a new instance of the [GetCountryRegionDataResponse](getcountryregiondataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionInfoList As ReadOnlyCollection(Of CountryRegionInfo), _
    addressFormattingInfoList As ReadOnlyCollection(Of AddressFormattingInfo) _
)
'Usage
Dim countryRegionInfoList As ReadOnlyCollection(Of CountryRegionInfo)
Dim addressFormattingInfoList As ReadOnlyCollection(Of AddressFormattingInfo)

Dim instance As New GetCountryRegionDataResponse(countryRegionInfoList, _
    addressFormattingInfoList)
```

``` csharp
public GetCountryRegionDataResponse(
    ReadOnlyCollection<CountryRegionInfo> countryRegionInfoList,
    ReadOnlyCollection<AddressFormattingInfo> addressFormattingInfoList
)
```

``` c++
public:
GetCountryRegionDataResponse(
    ReadOnlyCollection<CountryRegionInfo^>^ countryRegionInfoList, 
    ReadOnlyCollection<AddressFormattingInfo^>^ addressFormattingInfoList
)
```

#### Parameters

  - countryRegionInfoList  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CountryRegionInfo](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - addressFormattingInfoList  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[AddressFormattingInfo](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCountryRegionDataResponse Class](getcountryregiondataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

