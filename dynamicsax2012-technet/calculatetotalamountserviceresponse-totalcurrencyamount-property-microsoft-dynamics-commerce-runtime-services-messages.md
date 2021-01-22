---
title: CalculateTotalAmountServiceResponse.TotalCurrencyAmount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TotalCurrencyAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTotalAmountServiceResponse.TotalCurrencyAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculatetotalamountserviceresponse.totalcurrencyamount(v=AX.60)
ms:contentKeyID: 62209643
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTotalAmountServiceResponse.TotalCurrencyAmount
dev_langs:
- CSharp
- C++
- VB
---

# TotalCurrencyAmount Property

Gets the total channel currency amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TotalCurrencyAmount As CurrencyAmount
    Get
    Private Set
'Usage
Dim instance As CalculateTotalAmountServiceResponse
Dim value As CurrencyAmount

value = instance.TotalCurrencyAmount
```

``` csharp
[DataMemberAttribute]
public CurrencyAmount TotalCurrencyAmount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CurrencyAmount^ TotalCurrencyAmount {
    CurrencyAmount^ get ();
    private: void set (CurrencyAmount^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CalculateTotalAmountServiceResponse Class](calculatetotalamountserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

