---
title: GetChannelCurrencyAmountRequest.CurrenciesToConvert Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CurrenciesToConvert Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountRequest.CurrenciesToConvert
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcurrencyamountrequest.currenciestoconvert(v=AX.60)
ms:contentKeyID: 62210489
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountRequest.CurrenciesToConvert
dev_langs:
- CSharp
- C++
- VB
---

# CurrenciesToConvert Property

Gets or sets the currencies amount to be converted by the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CurrenciesToConvert As IEnumerable(Of CurrencyRequest)
    Get
    Set
'Usage
Dim instance As GetChannelCurrencyAmountRequest
Dim value As IEnumerable(Of CurrencyRequest)

value = instance.CurrenciesToConvert

instance.CurrenciesToConvert = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<CurrencyRequest> CurrenciesToConvert { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<CurrencyRequest^>^ CurrenciesToConvert {
    IEnumerable<CurrencyRequest^>^ get ();
    void set (IEnumerable<CurrencyRequest^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CurrencyRequest](currencyrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCurrencyAmountRequest Class](getchannelcurrencyamountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

