---
title: CustomerOrderInfo.SiteId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: SiteId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.SiteId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.siteid(v=AX.60)
ms:contentKeyID: 62208700
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.SiteId
dev_langs:
- CSharp
- C++
- VB
---

# SiteId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the site identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property SiteId As String
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As String

value = instance.SiteId

instance.SiteId = value
```

``` csharp
public string SiteId { get; set; }
```

``` c++
public:
property String^ SiteId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

