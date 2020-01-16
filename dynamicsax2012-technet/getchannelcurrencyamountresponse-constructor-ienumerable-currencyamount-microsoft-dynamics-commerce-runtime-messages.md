---
title: GetChannelCurrencyAmountResponse Constructor (IEnumerable(CurrencyAmount)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetChannelCurrencyAmountResponse Constructor (IEnumerable(CurrencyAmount))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcurrencyamountresponse.getchannelcurrencyamountresponse(v=AX.60)
ms:contentKeyID: 62207597
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelCurrencyAmountResponse Constructor (IEnumerable(CurrencyAmount))

Initializes a new instance of the [GetChannelCurrencyAmountResponse](getchannelcurrencyamountresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    currencies As IEnumerable(Of CurrencyAmount) _
)
'Usage
Dim currencies As IEnumerable(Of CurrencyAmount)

Dim instance As New GetChannelCurrencyAmountResponse(currencies)
```

``` csharp
public GetChannelCurrencyAmountResponse(
    IEnumerable<CurrencyAmount> currencies
)
```

``` c++
public:
GetChannelCurrencyAmountResponse(
    IEnumerable<CurrencyAmount^>^ currencies
)
```

#### Parameters

  - currencies  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChannelCurrencyAmountResponse Class](getchannelcurrencyamountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetChannelCurrencyAmountResponse Overload](getchannelcurrencyamountresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

