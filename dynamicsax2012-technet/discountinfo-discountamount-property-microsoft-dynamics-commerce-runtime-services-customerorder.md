---
title: DiscountInfo.DiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: DiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.DiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.discountinfo.discountamount(v=AX.60)
ms:contentKeyID: 62208861
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.DiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# DiscountAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property DiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As DiscountInfo
Dim value As Decimal

value = instance.DiscountAmount

instance.DiscountAmount = value
```

``` csharp
public decimal DiscountAmount { get; set; }
```

``` c++
public:
property Decimal DiscountAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[DiscountInfo Class](discountinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

