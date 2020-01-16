---
title: DiscountInfo.ManualDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: ManualDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.ManualDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.discountinfo.manualdiscounttype(v=AX.60)
ms:contentKeyID: 62210384
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.ManualDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# ManualDiscountType Property

Gets or sets the manual discount type.

Maps to enum RetailManualDiscountType in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property ManualDiscountType As Integer
    Get
    Set
'Usage
Dim instance As DiscountInfo
Dim value As Integer

value = instance.ManualDiscountType

instance.ManualDiscountType = value
```

``` csharp
public int ManualDiscountType { get; set; }
```

``` c++
public:
property int ManualDiscountType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DiscountInfo Class](discountinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

