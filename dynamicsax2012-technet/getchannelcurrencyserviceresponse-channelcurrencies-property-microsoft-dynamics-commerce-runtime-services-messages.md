---
title: GetChannelCurrencyServiceResponse.ChannelCurrencies Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ChannelCurrencies Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChannelCurrencyServiceResponse.ChannelCurrencies
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchannelcurrencyserviceresponse.channelcurrencies(v=AX.60)
ms:contentKeyID: 62209222
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChannelCurrencyServiceResponse.ChannelCurrencies
dev_langs:
- CSharp
- C++
- VB
---

# ChannelCurrencies Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the list of channel currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelCurrencies As ReadOnlyCollection(Of CurrencyAmount)
    Get
    Private Set
'Usage
Dim instance As GetChannelCurrencyServiceResponse
Dim value As ReadOnlyCollection(Of CurrencyAmount)

value = instance.ChannelCurrencies
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CurrencyAmount> ChannelCurrencies { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CurrencyAmount^>^ ChannelCurrencies {
    ReadOnlyCollection<CurrencyAmount^>^ get ();
    private: void set (ReadOnlyCollection<CurrencyAmount^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCurrencyServiceResponse Class](getchannelcurrencyserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

