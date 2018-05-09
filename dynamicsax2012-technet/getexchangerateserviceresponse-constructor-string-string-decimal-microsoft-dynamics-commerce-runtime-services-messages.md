---
title: GetExchangeRateServiceResponse Constructor (String, String, Decimal) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetExchangeRateServiceResponse Constructor (String, String, Decimal)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExchangeRateServiceResponse.#ctor(System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getexchangerateserviceresponse.getexchangerateserviceresponse(v=AX.60)
ms:contentKeyID: 62211522
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetExchangeRateServiceResponse Constructor (String, String, Decimal)

Initializes a new instance of the [GetExchangeRateServiceResponse](getexchangerateserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    fromCurrencyCode As String, _
    toCurrencyCode As String, _
    exchangeRate As Decimal _
)
'Usage
Dim fromCurrencyCode As String
Dim toCurrencyCode As String
Dim exchangeRate As Decimal

Dim instance As New GetExchangeRateServiceResponse(fromCurrencyCode, _
    toCurrencyCode, exchangeRate)
```

``` csharp
public GetExchangeRateServiceResponse(
    string fromCurrencyCode,
    string toCurrencyCode,
    decimal exchangeRate
)
```

``` c++
public:
GetExchangeRateServiceResponse(
    String^ fromCurrencyCode, 
    String^ toCurrencyCode, 
    Decimal exchangeRate
)
```

#### Parameters

  - fromCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - toCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - exchangeRate  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[GetExchangeRateServiceResponse Class](getexchangerateserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetExchangeRateServiceResponse Overload](getexchangerateserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

