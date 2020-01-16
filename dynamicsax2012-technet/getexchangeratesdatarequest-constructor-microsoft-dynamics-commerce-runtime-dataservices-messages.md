---
title: GetExchangeRatesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetExchangeRatesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest.#ctor(System.String,System.String,System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getexchangeratesdatarequest.getexchangeratesdatarequest(v=AX.60)
ms:contentKeyID: 65321145
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetExchangeRatesDataRequest Constructor

Initializes a new instance of the [GetExchangeRatesDataRequest](getexchangeratesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    fromCurrency As String, _
    toCurrency As String, _
    activeDate As DateTime _
)
'Usage
Dim fromCurrency As String
Dim toCurrency As String
Dim activeDate As DateTime

Dim instance As New GetExchangeRatesDataRequest(fromCurrency, _
    toCurrency, activeDate)
```

``` csharp
public GetExchangeRatesDataRequest(
    string fromCurrency,
    string toCurrency,
    DateTime activeDate
)
```

``` c++
public:
GetExchangeRatesDataRequest(
    String^ fromCurrency, 
    String^ toCurrency, 
    DateTime activeDate
)
```

#### Parameters

  - fromCurrency  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - toCurrency  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

## See Also

#### Reference

[GetExchangeRatesDataRequest Class](getexchangeratesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

