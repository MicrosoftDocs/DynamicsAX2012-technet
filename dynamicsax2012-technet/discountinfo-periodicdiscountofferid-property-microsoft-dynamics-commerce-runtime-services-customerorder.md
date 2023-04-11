---
title: DiscountInfo.PeriodicDiscountOfferId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: PeriodicDiscountOfferId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.PeriodicDiscountOfferId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.discountinfo.periodicdiscountofferid(v=AX.60)
ms:contentKeyID: 62213491
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.PeriodicDiscountOfferId
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountOfferId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the periodic discount offer identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property PeriodicDiscountOfferId As String
    Get
    Set
'Usage
Dim instance As DiscountInfo
Dim value As String

value = instance.PeriodicDiscountOfferId

instance.PeriodicDiscountOfferId = value
```

``` csharp
public string PeriodicDiscountOfferId { get; set; }
```

``` c++
public:
property String^ PeriodicDiscountOfferId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DiscountInfo Class](discountinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

