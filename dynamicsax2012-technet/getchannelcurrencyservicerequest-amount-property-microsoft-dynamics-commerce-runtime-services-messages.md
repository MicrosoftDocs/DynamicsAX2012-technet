---
title: GetChannelCurrencyServiceRequest.Amount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Amount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChannelCurrencyServiceRequest.Amount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchannelcurrencyservicerequest.amount(v=AX.60)
ms:contentKeyID: 62214724
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChannelCurrencyServiceRequest.Amount
dev_langs:
- CSharp
- C++
- VB
---

# Amount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the amount which is being converted by the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Amount As Decimal
    Get
    Private Set
'Usage
Dim instance As GetChannelCurrencyServiceRequest
Dim value As Decimal

value = instance.Amount
```

``` csharp
[DataMemberAttribute]
public decimal Amount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Amount {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCurrencyServiceRequest Class](getchannelcurrencyservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

