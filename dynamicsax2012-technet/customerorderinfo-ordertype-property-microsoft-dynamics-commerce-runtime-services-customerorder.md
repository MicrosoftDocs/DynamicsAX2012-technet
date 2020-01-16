---
title: CustomerOrderInfo.OrderType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: OrderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.OrderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.ordertype(v=AX.60)
ms:contentKeyID: 62206076
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.OrderType
dev_langs:
- CSharp
- C++
- VB
---

# OrderType Property

Gets or sets the customer order type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property OrderType As CustomerOrderType
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As CustomerOrderType

value = instance.OrderType

instance.OrderType = value
```

``` csharp
public CustomerOrderType OrderType { get; set; }
```

``` c++
public:
property CustomerOrderType OrderType {
    CustomerOrderType get ();
    void set (CustomerOrderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderType](customerordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CustomerOrderType](customerordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

