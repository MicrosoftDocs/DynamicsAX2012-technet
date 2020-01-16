---
title: GetCurrencyValueServiceResponse.ExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.ExchangeRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcurrencyvalueserviceresponse.exchangerate(v=AX.60)
ms:contentKeyID: 62207821
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.ExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# ExchangeRate Property

Gets the exchange rate of the targeted currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExchangeRate As Decimal
    Get
    Private Set
'Usage
Dim instance As GetCurrencyValueServiceResponse
Dim value As Decimal

value = instance.ExchangeRate
```

``` csharp
[DataMemberAttribute]
public decimal ExchangeRate { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ExchangeRate {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[GetCurrencyValueServiceResponse Class](getcurrencyvalueserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

