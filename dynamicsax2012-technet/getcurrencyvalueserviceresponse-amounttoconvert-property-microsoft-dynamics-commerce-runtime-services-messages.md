---
title: GetCurrencyValueServiceResponse.AmountToConvert Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AmountToConvert Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.AmountToConvert
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcurrencyvalueserviceresponse.amounttoconvert(v=AX.60)
ms:contentKeyID: 62213200
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.AmountToConvert
dev_langs:
- CSharp
- C++
- VB
---

# AmountToConvert Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the original currency amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AmountToConvert As Decimal
    Get
    Private Set
'Usage
Dim instance As GetCurrencyValueServiceResponse
Dim value As Decimal

value = instance.AmountToConvert
```

``` csharp
[DataMemberAttribute]
public decimal AmountToConvert { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal AmountToConvert {
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

