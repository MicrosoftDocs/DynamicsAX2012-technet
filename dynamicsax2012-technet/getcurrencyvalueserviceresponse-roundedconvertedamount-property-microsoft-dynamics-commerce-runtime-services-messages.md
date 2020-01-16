---
title: GetCurrencyValueServiceResponse.RoundedConvertedAmount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RoundedConvertedAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.RoundedConvertedAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcurrencyvalueserviceresponse.roundedconvertedamount(v=AX.60)
ms:contentKeyID: 62204228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.RoundedConvertedAmount
dev_langs:
- CSharp
- C++
- VB
---

# RoundedConvertedAmount Property

Gets the converted currency amount that has been rounded.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RoundedConvertedAmount As Decimal
    Get
    Private Set
'Usage
Dim instance As GetCurrencyValueServiceResponse
Dim value As Decimal

value = instance.RoundedConvertedAmount
```

``` csharp
[DataMemberAttribute]
public decimal RoundedConvertedAmount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal RoundedConvertedAmount {
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

