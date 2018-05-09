---
title: CustomerOrderInfo.HasLoyaltyPayment Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: HasLoyaltyPayment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.HasLoyaltyPayment
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.hasloyaltypayment(v=AX.60)
ms:contentKeyID: 62206534
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.HasLoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# HasLoyaltyPayment Property

Gets or sets a value indicating whether the customer order has any posted loyalty tender line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property HasLoyaltyPayment As Boolean
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Boolean

value = instance.HasLoyaltyPayment

instance.HasLoyaltyPayment = value
```

``` csharp
public bool HasLoyaltyPayment { get; set; }
```

``` c++
public:
property bool HasLoyaltyPayment {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

