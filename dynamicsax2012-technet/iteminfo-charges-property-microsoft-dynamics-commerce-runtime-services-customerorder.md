---
title: ItemInfo.Charges Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: Charges Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.Charges
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.iteminfo.charges(v=AX.60)
ms:contentKeyID: 62208724
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.Charges
dev_langs:
- CSharp
- C++
- VB
---

# Charges Property

Gets the the collection of line level charges for mixed delivery.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property Charges As Collection(Of ChargeInfo)
    Get
    Private Set
'Usage
Dim instance As ItemInfo
Dim value As Collection(Of ChargeInfo)

value = instance.Charges
```

``` csharp
public Collection<ChargeInfo> Charges { get; private set; }
```

``` c++
public:
property Collection<ChargeInfo^>^ Charges {
    Collection<ChargeInfo^>^ get ();
    private: void set (Collection<ChargeInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ChargeInfo](chargeinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ItemInfo Class](iteminfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

