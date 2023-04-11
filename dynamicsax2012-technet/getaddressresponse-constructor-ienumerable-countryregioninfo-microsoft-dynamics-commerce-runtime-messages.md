---
title: GetAddressResponse Constructor (IEnumerable(CountryRegionInfo)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAddressResponse Constructor (IEnumerable(CountryRegionInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.getaddressresponse(v=AX.60)
ms:contentKeyID: 62214563
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAddressResponse Constructor (IEnumerable(CountryRegionInfo))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetAddressResponse](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countries As IEnumerable(Of CountryRegionInfo) _
)
'Usage
Dim countries As IEnumerable(Of CountryRegionInfo)

Dim instance As New GetAddressResponse(countries)
```

``` csharp
public GetAddressResponse(
    IEnumerable<CountryRegionInfo> countries
)
```

``` c++
public:
GetAddressResponse(
    IEnumerable<CountryRegionInfo^>^ countries
)
```

#### Parameters

  - countries  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CountryRegionInfo](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAddressResponse Overload](getaddressresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

