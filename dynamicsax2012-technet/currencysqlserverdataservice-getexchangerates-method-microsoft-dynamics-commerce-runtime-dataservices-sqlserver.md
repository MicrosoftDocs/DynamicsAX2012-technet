---
title: CurrencySqlServerDataService.GetExchangeRates Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer)
TOCTitle: GetExchangeRates Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.CurrencySqlServerDataService.GetExchangeRates(Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.currencysqlserverdataservice.getexchangerates(v=AX.60)
ms:contentKeyID: 65316997
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.CurrencySqlServerDataService.GetExchangeRates
dev_langs:
- CSharp
- C++
- VB
---

# GetExchangeRates Method

Gets the exchange rate active on given date between these currencies on this channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function GetExchangeRates ( _
    request As GetExchangeRatesDataRequest _
) As EntityDataServiceResponse(Of ExchangeRate)
'Usage
Dim instance As CurrencySqlServerDataService
Dim request As GetExchangeRatesDataRequest
Dim returnValue As EntityDataServiceResponse(Of ExchangeRate)

returnValue = instance.GetExchangeRates(request)
```

``` csharp
public EntityDataServiceResponse<ExchangeRate> GetExchangeRates(
    GetExchangeRatesDataRequest request
)
```

``` c++
public:
EntityDataServiceResponse<ExchangeRate^>^ GetExchangeRates(
    GetExchangeRatesDataRequest^ request
)
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest](getexchangeratesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse](entitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)\<[ExchangeRate](exchangerate-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The data service response with up to two exchange rates, which are forward and backward rates between the currencies.  

## See Also

#### Reference

[CurrencySqlServerDataService Class](currencysqlserverdataservice-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-namespace.md)

