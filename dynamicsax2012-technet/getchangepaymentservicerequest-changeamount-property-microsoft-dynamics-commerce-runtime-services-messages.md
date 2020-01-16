---
title: GetChangePaymentServiceRequest.ChangeAmount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ChangeAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest.ChangeAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchangepaymentservicerequest.changeamount(v=AX.60)
ms:contentKeyID: 65319090
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest.ChangeAmount
dev_langs:
- CSharp
- C++
- VB
---

# ChangeAmount Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChangeAmount As Decimal
    Get
    Set
'Usage
Dim instance As GetChangePaymentServiceRequest
Dim value As Decimal

value = instance.ChangeAmount

instance.ChangeAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal ChangeAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ChangeAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[GetChangePaymentServiceRequest Class](getchangepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

