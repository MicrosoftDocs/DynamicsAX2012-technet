---
title: PaymentInfo.Prepayment Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: Prepayment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.PaymentInfo.Prepayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.paymentinfo.prepayment(v=AX.60)
ms:contentKeyID: 62204726
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.PaymentInfo.Prepayment
dev_langs:
- CSharp
- C++
- VB
---

# Prepayment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether prepayment was made.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property Prepayment As Boolean
    Get
    Set
'Usage
Dim instance As PaymentInfo
Dim value As Boolean

value = instance.Prepayment

instance.Prepayment = value
```

``` csharp
public bool Prepayment { get; set; }
```

``` c++
public:
property bool Prepayment {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PaymentInfo Class](paymentinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

