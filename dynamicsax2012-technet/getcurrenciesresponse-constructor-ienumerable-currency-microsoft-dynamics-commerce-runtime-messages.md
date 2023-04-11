---
title: GetCurrenciesResponse Constructor (IEnumerable(Currency)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetCurrenciesResponse Constructor (IEnumerable(Currency))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrenciesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcurrenciesresponse.getcurrenciesresponse(v=AX.60)
ms:contentKeyID: 62210006
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCurrenciesResponse Constructor (IEnumerable(Currency))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCurrenciesResponse](getcurrenciesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    currencies As IEnumerable(Of Currency) _
)
'Usage
Dim currencies As IEnumerable(Of Currency)

Dim instance As New GetCurrenciesResponse(currencies)
```

``` csharp
public GetCurrenciesResponse(
    IEnumerable<Currency> currencies
)
```

``` c++
public:
GetCurrenciesResponse(
    IEnumerable<Currency^>^ currencies
)
```

#### Parameters

  - currencies  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Currency](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCurrenciesResponse Class](getcurrenciesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetCurrenciesResponse Overload](getcurrenciesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

