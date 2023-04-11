---
title: CustomerOrderInfo.DocumentStatus Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: DocumentStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.DocumentStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.documentstatus(v=AX.60)
ms:contentKeyID: 62211143
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.DocumentStatus
dev_langs:
- CSharp
- C++
- VB
---

# DocumentStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the document status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property DocumentStatus As Integer
    Get
    Set
'Usage
Dim instance As CustomerOrderInfo
Dim value As Integer

value = instance.DocumentStatus

instance.DocumentStatus = value
```

``` csharp
public int DocumentStatus { get; set; }
```

``` c++
public:
property int DocumentStatus {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

