---
title: CalculateTotalAmountServiceRequest.CurrenciesToConvert Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CurrenciesToConvert Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTotalAmountServiceRequest.CurrenciesToConvert
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.calculatetotalamountservicerequest.currenciestoconvert(v=AX.60)
ms:contentKeyID: 62214926
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTotalAmountServiceRequest.CurrenciesToConvert
dev_langs:
- CSharp
- C++
- VB
---

# CurrenciesToConvert Property

Gets or sets the currencies amount to be converted by the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CurrenciesToConvert As IEnumerable(Of CurrencyRequest)
    Get
    Set
'Usage
Dim instance As CalculateTotalAmountServiceRequest
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

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CurrencyRequest](currencyrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[CalculateTotalAmountServiceRequest Class](calculatetotalamountservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

