---
title: CurrencyDataManager.GetChannelCurrencies Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelCurrencies Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyDataManager.GetChannelCurrencies(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.currencydatamanager.getchannelcurrencies(v=AX.60)
ms:contentKeyID: 65322538
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyDataManager.GetChannelCurrencies
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCurrencies Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelCurrencies ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of CurrencyAmount)
'Usage
Dim instance As CurrencyDataManager
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

#### Implements

[ICurrencyDataManager.GetChannelCurrencies(QueryResultSettings)](icurrencydatamanager-getchannelcurrencies-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[CurrencyDataManager Class](currencydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

