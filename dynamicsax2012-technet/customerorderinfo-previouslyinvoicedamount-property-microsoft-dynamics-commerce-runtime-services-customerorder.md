---
title: CustomerOrderInfo.PreviouslyInvoicedAmount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: PreviouslyInvoicedAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.PreviouslyInvoicedAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.previouslyinvoicedamount(v=AX.60)
ms:contentKeyID: 62204584
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.PreviouslyInvoicedAmount
dev_langs:
- CSharp
- C++
- VB
---

# PreviouslyInvoicedAmount Property

Gets or sets the amount that has been previously invoiced (picked-up).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property PreviouslyInvoicedAmount As Decimal
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Decimal

value = instance.PreviouslyInvoicedAmount

instance.PreviouslyInvoicedAmount = value
```

``` csharp
public decimal PreviouslyInvoicedAmount { get; set; }
```

``` c++
public:
property Decimal PreviouslyInvoicedAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

