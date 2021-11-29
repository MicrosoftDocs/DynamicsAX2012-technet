---
title: DiscountInfo.DealPrice Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: DealPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.DealPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.discountinfo.dealprice(v=AX.60)
ms:contentKeyID: 62209235
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.DealPrice
dev_langs:
- CSharp
- C++
- VB
---

# DealPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the deal price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property DealPrice As Decimal
    Get
    Set
'Usage
Dim instance As DiscountInfo
Dim value As Decimal

value = instance.DealPrice

instance.DealPrice = value
```

``` csharp
public decimal DealPrice { get; set; }
```

``` c++
public:
property Decimal DealPrice {
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

