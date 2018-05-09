---
title: GetCurrencyValueServiceResponse Constructor (String, String, Decimal, Decimal, Decimal, Decimal) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCurrencyValueServiceResponse Constructor (String, String, Decimal, Decimal, Decimal, Decimal)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.#ctor(System.String,System.String,System.Decimal,System.Decimal,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcurrencyvalueserviceresponse.getcurrencyvalueserviceresponse(v=AX.60)
ms:contentKeyID: 62214924
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCurrencyValueServiceResponse Constructor (String, String, Decimal, Decimal, Decimal, Decimal)

Initializes a new instance of the [GetCurrencyValueServiceResponse](getcurrencyvalueserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    fromCurrencyCode As String, _
    toCurrencyCode As String, _
    amountToConvert As Decimal, _
    convertedAmount As Decimal, _
    roundedConvertedAmount As Decimal, _
    toExchangeRate As Decimal _
)
'Usage
Dim fromCurrencyCode As String
Dim toCurrencyCode As String
Dim amountToConvert As Decimal
Dim convertedAmount As Decimal
Dim roundedConvertedAmount As Decimal
Dim toExchangeRate As Decimal

Dim instance As New GetCurrencyValueServiceResponse(fromCurrencyCode, _
    toCurrencyCode, amountToConvert, _
    convertedAmount, roundedConvertedAmount, _
    toExchangeRate)
```

``` csharp
public GetCurrencyValueServiceResponse(
    string fromCurrencyCode,
    string toCurrencyCode,
    decimal amountToConvert,
    decimal convertedAmount,
    decimal roundedConvertedAmount,
    decimal toExchangeRate
)
```

``` c++
public:
GetCurrencyValueServiceResponse(
    String^ fromCurrencyCode, 
    String^ toCurrencyCode, 
    Decimal amountToConvert, 
    Decimal convertedAmount, 
    Decimal roundedConvertedAmount, 
    Decimal toExchangeRate
)
```

#### Parameters

  - fromCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - toCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amountToConvert  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - convertedAmount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - roundedConvertedAmount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - toExchangeRate  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[GetCurrencyValueServiceResponse Class](getcurrencyvalueserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCurrencyValueServiceResponse Overload](getcurrencyvalueserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

