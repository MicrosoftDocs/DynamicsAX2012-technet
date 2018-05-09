---
title: DiscountInfo.CustomerDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: CustomerDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.CustomerDiscountType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.customerorder.discountinfo.customerdiscounttype(v=AX.60)
ms:contentKeyID: 62209826
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.DiscountInfo.CustomerDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDiscountType Property

Gets or sets the customer dicount type.

Maps to enum RetailCustomerDiscountType in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerDiscountType As Integer
    Get
    Set
'Usage
Dim instance As DiscountInfo
Dim value As Integer

value = instance.CustomerDiscountType

instance.CustomerDiscountType = value
```

``` csharp
public int CustomerDiscountType { get; set; }
```

``` c++
public:
property int CustomerDiscountType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DiscountInfo Class](discountinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

