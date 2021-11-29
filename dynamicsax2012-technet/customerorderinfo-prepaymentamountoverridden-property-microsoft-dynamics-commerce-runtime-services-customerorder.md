---
title: CustomerOrderInfo.PrepaymentAmountOverridden Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: PrepaymentAmountOverridden Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.PrepaymentAmountOverridden
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.prepaymentamountoverridden(v=AX.60)
ms:contentKeyID: 62208094
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.PrepaymentAmountOverridden
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountOverridden Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the prepayment (deposit) amount was overridden.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property PrepaymentAmountOverridden As Boolean
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Boolean

value = instance.PrepaymentAmountOverridden

instance.PrepaymentAmountOverridden = value
```

``` csharp
public bool PrepaymentAmountOverridden { get; set; }
```

``` c++
public:
property bool PrepaymentAmountOverridden {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

