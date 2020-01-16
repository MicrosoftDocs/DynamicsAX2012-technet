---
title: CustomerOrderInfo.PrepaymentAmountApplied Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: PrepaymentAmountApplied Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.PrepaymentAmountApplied
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.prepaymentamountapplied(v=AX.60)
ms:contentKeyID: 62208653
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.PrepaymentAmountApplied
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountApplied Property

Gets or sets the amount of prepayment that is currently applied to this order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property PrepaymentAmountApplied As Decimal
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Decimal

value = instance.PrepaymentAmountApplied

instance.PrepaymentAmountApplied = value
```

``` csharp
public decimal PrepaymentAmountApplied { get; set; }
```

``` c++
public:
property Decimal PrepaymentAmountApplied {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

