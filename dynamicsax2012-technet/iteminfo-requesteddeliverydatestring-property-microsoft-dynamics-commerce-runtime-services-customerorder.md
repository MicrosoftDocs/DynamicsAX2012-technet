---
title: ItemInfo.RequestedDeliveryDateString Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: RequestedDeliveryDateString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.RequestedDeliveryDateString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.iteminfo.requesteddeliverydatestring(v=AX.60)
ms:contentKeyID: 62212149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.RequestedDeliveryDateString
dev_langs:
- CSharp
- C++
- VB
---

# RequestedDeliveryDateString Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the expiry Date in string format.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property RequestedDeliveryDateString As String
    Get
    Set
'Usage
Dim instance As ItemInfo
Dim value As String

value = instance.RequestedDeliveryDateString

instance.RequestedDeliveryDateString = value
```

``` csharp
public string RequestedDeliveryDateString { get; set; }
```

``` c++
public:
property String^ RequestedDeliveryDateString {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemInfo Class](iteminfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

