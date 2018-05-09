---
title: GetAddressResponse Constructor (IEnumerable(CityInfo)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAddressResponse Constructor (IEnumerable(CityInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CityInfo})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.getaddressresponse(v=AX.60)
ms:contentKeyID: 62212592
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAddressResponse Constructor (IEnumerable(CityInfo))

Initializes a new instance of the [GetAddressResponse](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cities As IEnumerable(Of CityInfo) _
)
'Usage
Dim cities As IEnumerable(Of CityInfo)

Dim instance As New GetAddressResponse(cities)
```

``` csharp
public GetAddressResponse(
    IEnumerable<CityInfo> cities
)
```

``` c++
public:
GetAddressResponse(
    IEnumerable<CityInfo^>^ cities
)
```

#### Parameters

  - cities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CityInfo](cityinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAddressResponse Overload](getaddressresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

