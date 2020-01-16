---
title: CustomerOrderInfo.Payments Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: Payments Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.Payments
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.payments(v=AX.60)
ms:contentKeyID: 62214896
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.Payments
dev_langs:
- CSharp
- C++
- VB
---

# Payments Property

Gets the collection of payment information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property Payments As Collection(Of PaymentInfo)
    Get
    Private Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Collection(Of PaymentInfo)

value = instance.Payments
```

``` csharp
public Collection<PaymentInfo> Payments { get; private set; }
```

``` c++
public:
property Collection<PaymentInfo^>^ Payments {
    Collection<PaymentInfo^>^ get ();
    private: void set (Collection<PaymentInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[PaymentInfo](paymentinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

