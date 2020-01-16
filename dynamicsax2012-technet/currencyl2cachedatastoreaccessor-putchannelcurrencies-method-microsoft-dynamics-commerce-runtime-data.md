---
title: CurrencyL2CacheDataStoreAccessor.PutChannelCurrencies Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelCurrencies Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.PutChannelCurrencies(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.currencyl2cachedatastoreaccessor.putchannelcurrencies(v=AX.60)
ms:contentKeyID: 65320593
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyL2CacheDataStoreAccessor.PutChannelCurrencies
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelCurrencies Method

Caches the list of supported channel currencies.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutChannelCurrencies ( _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of CurrencyAmount) _
)
'Usage
Dim instance As CurrencyL2CacheDataStoreAccessor
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of CurrencyAmount)

instance.PutChannelCurrencies(settings, _
    result)
```

``` csharp
public void PutChannelCurrencies(
    QueryResultSettings settings,
    ReadOnlyCollection<CurrencyAmount> result
)
```

``` c++
public:
void PutChannelCurrencies(
    QueryResultSettings^ settings, 
    ReadOnlyCollection<CurrencyAmount^>^ result
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CurrencyL2CacheDataStoreAccessor Class](currencyl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

