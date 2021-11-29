---
title: GetCardPaymentPropertiesServiceResponse.AvailableBalance Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AvailableBalance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceResponse.AvailableBalance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcardpaymentpropertiesserviceresponse.availablebalance(v=AX.60)
ms:contentKeyID: 65322899
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceResponse.AvailableBalance
dev_langs:
- CSharp
- C++
- VB
---

# AvailableBalance Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AvailableBalance As Decimal
    Get
    Private Set
'Usage
Dim instance As GetCardPaymentPropertiesServiceResponse
Dim value As Decimal

value = instance.AvailableBalance
```

``` csharp
[DataMemberAttribute]
public decimal AvailableBalance { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal AvailableBalance {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[GetCardPaymentPropertiesServiceResponse Class](getcardpaymentpropertiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

