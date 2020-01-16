---
title: CustomerOrderInfo.AutoPickOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: AutoPickOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.AutoPickOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.autopickorder(v=AX.60)
ms:contentKeyID: 62211092
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.AutoPickOrder
dev_langs:
- CSharp
- C++
- VB
---

# AutoPickOrder Property

Gets or sets a value indicating whether or not to Automatically create a pick list for the order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property AutoPickOrder As Boolean
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Boolean

value = instance.AutoPickOrder

instance.AutoPickOrder = value
```

``` csharp
public bool AutoPickOrder { get; set; }
```

``` c++
public:
property bool AutoPickOrder {
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

