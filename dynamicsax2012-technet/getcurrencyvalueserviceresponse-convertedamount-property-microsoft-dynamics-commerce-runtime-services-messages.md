---
title: GetCurrencyValueServiceResponse.ConvertedAmount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ConvertedAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.ConvertedAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcurrencyvalueserviceresponse.convertedamount(v=AX.60)
ms:contentKeyID: 62207117
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.ConvertedAmount
dev_langs:
- CSharp
- C++
- VB
---

# ConvertedAmount Property

Gets the converted currency amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ConvertedAmount As Decimal
    Get
    Private Set
'Usage
Dim instance As GetCurrencyValueServiceResponse
Dim value As Decimal

value = instance.ConvertedAmount
```

``` csharp
[DataMemberAttribute]
public decimal ConvertedAmount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ConvertedAmount {
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

