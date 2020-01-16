---
title: ICurrencyDataManager.GetChannelCurrencies Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelCurrencies Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICurrencyDataManager.GetChannelCurrencies(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icurrencydatamanager.getchannelcurrencies(v=AX.60)
ms:contentKeyID: 65316259
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICurrencyDataManager.GetChannelCurrencies
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
Function GetChannelCurrencies ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of CurrencyAmount)
'Usage
Dim instance As ICurrencyDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of CurrencyAmount)

returnValue = instance.GetChannelCurrencies(settings)
```

``` csharp
ReadOnlyCollection<CurrencyAmount> GetChannelCurrencies(
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<CurrencyAmount^>^ GetChannelCurrencies(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the supported channel currencies.  

## See Also

#### Reference

[ICurrencyDataManager Interface](icurrencydatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

