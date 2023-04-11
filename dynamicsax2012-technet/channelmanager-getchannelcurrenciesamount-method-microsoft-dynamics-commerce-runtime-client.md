---
title: ChannelManager.GetChannelCurrenciesAmount Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelCurrenciesAmount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelCurrenciesAmount(System.String,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getchannelcurrenciesamount(v=AX.60)
ms:contentKeyID: 65319333
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelCurrenciesAmount
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCurrenciesAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelCurrenciesAmount ( _
    fromCurrencyCode As String, _
    fromAmount As Decimal, _
    settings As QueryResultSettings _
) As PagedResult(Of CurrencyAmount)
'Usage
Dim instance As ChannelManager
Dim fromCurrencyCode As String
Dim fromAmount As Decimal
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of CurrencyAmount)

returnValue = instance.GetChannelCurrenciesAmount(fromCurrencyCode, _
    fromAmount, settings)
```

``` csharp
public PagedResult<CurrencyAmount> GetChannelCurrenciesAmount(
    string fromCurrencyCode,
    decimal fromAmount,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<CurrencyAmount^>^ GetChannelCurrenciesAmount(
    String^ fromCurrencyCode, 
    Decimal fromAmount, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - fromCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - fromAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

