---
title: CurrencyL2CacheDataStoreAccessor.PutExchangeRates Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutExchangeRates Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.PutExchangeRates(System.String,System.String,System.DateTime,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.currencyl2cachedatastoreaccessor.putexchangerates(v=AX.60)
ms:contentKeyID: 65322780
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.PutExchangeRates
dev_langs:
- CSharp
- C++
- VB
---

# PutExchangeRates Method

Caches the exchange rate active on given date between these currencies on this channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutExchangeRates ( _
    fromCurrency As String, _
    toCurrency As String, _
    activeDate As DateTime, _
    result As ReadOnlyCollection(Of ExchangeRate) _
)
'Usage
Dim instance As CurrencyL2CacheDataStoreAccessor
Dim fromCurrency As String
Dim toCurrency As String
Dim activeDate As DateTime
Dim result As ReadOnlyCollection(Of ExchangeRate)

instance.PutExchangeRates(fromCurrency, _
    toCurrency, activeDate, result)
```

``` csharp
public void PutExchangeRates(
    string fromCurrency,
    string toCurrency,
    DateTime activeDate,
    ReadOnlyCollection<ExchangeRate> result
)
```

``` c++
public:
void PutExchangeRates(
    String^ fromCurrency, 
    String^ toCurrency, 
    DateTime activeDate, 
    ReadOnlyCollection<ExchangeRate^>^ result
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

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ExchangeRate](exchangerate-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CurrencyL2CacheDataStoreAccessor Class](currencyl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

