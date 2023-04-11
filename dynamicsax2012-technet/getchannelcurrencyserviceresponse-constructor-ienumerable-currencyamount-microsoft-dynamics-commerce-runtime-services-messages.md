---
title: GetChannelCurrencyServiceResponse Constructor (IEnumerable(CurrencyAmount)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetChannelCurrencyServiceResponse Constructor (IEnumerable(CurrencyAmount))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChannelCurrencyServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchannelcurrencyserviceresponse.getchannelcurrencyserviceresponse(v=AX.60)
ms:contentKeyID: 62202113
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelCurrencyServiceResponse Constructor (IEnumerable(CurrencyAmount))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetChannelCurrencyServiceResponse](getchannelcurrencyserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    currencies As IEnumerable(Of CurrencyAmount) _
)
'Usage
Dim currencies As IEnumerable(Of CurrencyAmount)

Dim instance As New GetChannelCurrencyServiceResponse(currencies)
```

``` csharp
public GetChannelCurrencyServiceResponse(
    IEnumerable<CurrencyAmount> currencies
)
```

``` c++
public:
GetChannelCurrencyServiceResponse(
    IEnumerable<CurrencyAmount^>^ currencies
)
```

#### Parameters

  - currencies  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChannelCurrencyServiceResponse Class](getchannelcurrencyserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetChannelCurrencyServiceResponse Overload](getchannelcurrencyserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

