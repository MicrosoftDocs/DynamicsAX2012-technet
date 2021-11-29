---
title: OrderManager.UploadOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UploadOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UploadOrder(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.uploadorder(v=AX.60)
ms:contentKeyID: 62209369
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UploadOrder
dev_langs:
- CSharp
- C++
- VB
---

# UploadOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Upload a booked sales order with tender lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub UploadOrder ( _
    order As SalesOrder _
)
'Usage
Dim instance As OrderManager
Dim order As SalesOrder

instance.UploadOrder(order)
```

``` csharp
public void UploadOrder(
    SalesOrder order
)
```

``` c++
public:
void UploadOrder(
    SalesOrder^ order
)
```

#### Parameters

  - order  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

