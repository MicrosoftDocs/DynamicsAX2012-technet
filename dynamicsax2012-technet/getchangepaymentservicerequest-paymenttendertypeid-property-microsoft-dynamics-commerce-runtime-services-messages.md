---
title: GetChangePaymentServiceRequest.PaymentTenderTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PaymentTenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest.PaymentTenderTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchangepaymentservicerequest.paymenttendertypeid(v=AX.60)
ms:contentKeyID: 62207823
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest.PaymentTenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# PaymentTenderTypeId Property

Gets the tender type identifier of the payment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentTenderTypeId As String
    Get
    Private Set
'Usage
Dim instance As GetChangePaymentServiceRequest
Dim value As String

value = instance.PaymentTenderTypeId
```

``` csharp
[DataMemberAttribute]
public string PaymentTenderTypeId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PaymentTenderTypeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetChangePaymentServiceRequest Class](getchangepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

