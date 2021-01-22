---
title: CurrencyL2CacheDataStoreAccessor.GetChannelCurrencies Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelCurrencies Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.GetChannelCurrencies(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.currencyl2cachedatastoreaccessor.getchannelcurrencies(v=AX.60)
ms:contentKeyID: 65320490
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.GetChannelCurrencies
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCurrencies Method

Gets the list of supported channel currencies.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelCurrencies ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of CurrencyAmount)
'Usage
Dim instance As CurrencyL2CacheDataStoreAccessor
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of CurrencyAmount)

returnValue = instance.GetChannelCurrencies(settings)
```

``` csharp
public ReadOnlyCollection<CurrencyAmount> GetChannelCurrencies(
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<CurrencyAmount^>^ GetChannelCurrencies(
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the supported channel currencies.  

#### Implements

[ICurrencyDataManager.GetChannelCurrencies(QueryResultSettings)](icurrencydatamanager-getchannelcurrencies-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[CurrencyL2CacheDataStoreAccessor Class](currencyl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

