---
title: CustomerOrderInfo.Preauthorization Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: Preauthorization Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.Preauthorization
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.preauthorization(v=AX.60)
ms:contentKeyID: 62205361
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.Preauthorization
dev_langs:
- CSharp
- C++
- VB
---

# Preauthorization Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the information to void a prior authorization.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property Preauthorization As Preauthorization
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Preauthorization

value = instance.Preauthorization

instance.Preauthorization = value
```

``` csharp
public Preauthorization Preauthorization { get; set; }
```

``` c++
public:
property Preauthorization^ Preauthorization {
    Preauthorization^ get ();
    void set (Preauthorization^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.Preauthorization](preauthorization-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)  
Returns [Preauthorization](preauthorization-class-microsoft-dynamics-commerce-runtime-services-customerorder.md).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

