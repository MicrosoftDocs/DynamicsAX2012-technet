---
title: SaveCustomerOrderRequest.PaymentCard Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PaymentCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.PaymentCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecustomerorderrequest.paymentcard(v=AX.60)
ms:contentKeyID: 62208499
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.PaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# PaymentCard Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the payment cards.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentCard As PaymentCard
    Get
    Private Set
'Usage
Dim instance As SaveCustomerOrderRequest
Dim value As PaymentCard

value = instance.PaymentCard
```

``` csharp
[DataMemberAttribute]
public PaymentCard PaymentCard { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PaymentCard^ PaymentCard {
    PaymentCard^ get ();
    private: void set (PaymentCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveCustomerOrderRequest Class](savecustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

