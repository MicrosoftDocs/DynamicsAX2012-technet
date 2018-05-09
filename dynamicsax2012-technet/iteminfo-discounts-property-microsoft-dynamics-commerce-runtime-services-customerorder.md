---
title: ItemInfo.Discounts Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: Discounts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.Discounts
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.customerorder.iteminfo.discounts(v=AX.60)
ms:contentKeyID: 62213269
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.Discounts
dev_langs:
- CSharp
- C++
- VB
---

# Discounts Property

Gets the the collection of line level discounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property Discounts As Collection(Of DiscountInfo)
    Get
    Private Set
'Usage
Dim instance As ItemInfo
Dim value As Collection(Of DiscountInfo)

value = instance.Discounts
```

``` csharp
public Collection<DiscountInfo> Discounts { get; private set; }
```

``` c++
public:
property Collection<DiscountInfo^>^ Discounts {
    Collection<DiscountInfo^>^ get ();
    private: void set (Collection<DiscountInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[DiscountInfo](discountinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ItemInfo Class](iteminfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

