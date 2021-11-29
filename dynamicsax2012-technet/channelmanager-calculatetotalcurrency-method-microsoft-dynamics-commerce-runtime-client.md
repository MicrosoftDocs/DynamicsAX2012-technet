---
title: ChannelManager.CalculateTotalCurrency Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CalculateTotalCurrency Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.CalculateTotalCurrency(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyRequest},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.calculatetotalcurrency(v=AX.60)
ms:contentKeyID: 65322038
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.CalculateTotalCurrency
dev_langs:
- CSharp
- C++
- VB
---

# CalculateTotalCurrency Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function CalculateTotalCurrency ( _
    currencyToConvert As IEnumerable(Of CurrencyRequest), _
    settings As QueryResultSettings _
) As CurrencyAmount
'Usage
Dim instance As ChannelManager
Dim currencyToConvert As IEnumerable(Of CurrencyRequest)
Dim settings As QueryResultSettings
Dim returnValue As CurrencyAmount

returnValue = instance.CalculateTotalCurrency(currencyToConvert, _
    settings)
```

``` csharp
public CurrencyAmount CalculateTotalCurrency(
    IEnumerable<CurrencyRequest> currencyToConvert,
    QueryResultSettings settings
)
```

``` c++
public:
CurrencyAmount^ CalculateTotalCurrency(
    IEnumerable<CurrencyRequest^>^ currencyToConvert, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - currencyToConvert  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CurrencyRequest](currencyrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

