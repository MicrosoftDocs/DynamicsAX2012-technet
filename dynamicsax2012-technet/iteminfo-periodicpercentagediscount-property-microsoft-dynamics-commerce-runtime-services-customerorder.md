---
title: ItemInfo.PeriodicPercentageDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: PeriodicPercentageDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.PeriodicPercentageDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.iteminfo.periodicpercentagediscount(v=AX.60)
ms:contentKeyID: 62213420
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.PeriodicPercentageDiscount
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicPercentageDiscount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the periodic percentage discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property PeriodicPercentageDiscount As Decimal
    Get
    Set
'Usage
Dim instance As ItemInfo
Dim value As Decimal

value = instance.PeriodicPercentageDiscount

instance.PeriodicPercentageDiscount = value
```

``` csharp
public decimal PeriodicPercentageDiscount { get; set; }
```

``` c++
public:
property Decimal PeriodicPercentageDiscount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ItemInfo Class](iteminfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

