---
title: CurrencyL2CacheDataStoreAccessor.GetExchangeRates Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetExchangeRates Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.GetExchangeRates(System.String,System.String,System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.currencyl2cachedatastoreaccessor.getexchangerates(v=AX.60)
ms:contentKeyID: 65319876
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.GetExchangeRates
dev_langs:
- CSharp
- C++
- VB
---

# GetExchangeRates Method

Gets the exchange rate active on given date between these currencies on this channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetExchangeRates ( _
    fromCurrency As String, _
    toCurrency As String, _
    activeDate As DateTime _
) As ReadOnlyCollection(Of ExchangeRate)
'Usage
Dim instance As CurrencyL2CacheDataStoreAccessor
Dim fromCurrency As String
Dim toCurrency As String
Dim activeDate As DateTime
Dim returnValue As ReadOnlyCollection(Of ExchangeRate)

returnValue = instance.GetExchangeRates(fromCurrency, _
    toCurrency, activeDate)
```

``` csharp
public ReadOnlyCollection<ExchangeRate> GetExchangeRates(
    string fromCurrency,
    string toCurrency,
    DateTime activeDate
)
```

``` c++
public:
ReadOnlyCollection<ExchangeRate^>^ GetExchangeRates(
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

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ExchangeRate](exchangerate-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns up to two exchange rates, which are forward and backward rates between the currencies.  

## See Also

#### Reference

[CurrencyL2CacheDataStoreAccessor Class](currencyl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

