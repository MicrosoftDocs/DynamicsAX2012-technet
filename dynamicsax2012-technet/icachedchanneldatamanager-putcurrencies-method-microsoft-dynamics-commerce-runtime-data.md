---
title: ICachedChannelDataManager.PutCurrencies Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutCurrencies Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutCurrencies(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putcurrencies(v=AX.60)
ms:contentKeyID: 65323123
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutCurrencies
dev_langs:
- CSharp
- C++
- VB
---

# PutCurrencies Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutCurrencies ( _
    currency As String, _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of Currency) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim currency As String
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of Currency)

instance.PutCurrencies(currency, settings, _
    result)
```

``` csharp
void PutCurrencies(
    string currency,
    QueryResultSettings settings,
    ReadOnlyCollection<Currency> result
)
```

``` c++
void PutCurrencies(
    String^ currency, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<Currency^>^ result
)
```

#### Parameters

  - currency  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Currency](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

