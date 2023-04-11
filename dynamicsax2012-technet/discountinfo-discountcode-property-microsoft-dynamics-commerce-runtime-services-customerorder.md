---
title: DiscountInfo.DiscountCode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: DiscountCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.DiscountCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.discountinfo.discountcode(v=AX.60)
ms:contentKeyID: 62207972
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.DiscountCode
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property DiscountCode As String
    Get
    Set
'Usage
Dim instance As DiscountInfo
Dim value As String

value = instance.DiscountCode

instance.DiscountCode = value
```

``` csharp
public string DiscountCode { get; set; }
```

``` c++
public:
property String^ DiscountCode {
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

