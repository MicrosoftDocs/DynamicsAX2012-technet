---
title: GetPurchaseOrderServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetPurchaseOrderServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPurchaseOrderServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpurchaseorderserviceresponse.getpurchaseorderserviceresponse(v=AX.60)
ms:contentKeyID: 62202813
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPurchaseOrderServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetPurchaseOrderServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the GetPurchaseOrderServiceResponse class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    purchaseOrders As IEnumerable(Of PurchaseOrder) _
)
'Usage
Dim purchaseOrders As IEnumerable(Of PurchaseOrder)

Dim instance As New GetPurchaseOrderServiceResponse(purchaseOrders)
```

``` csharp
public GetPurchaseOrderServiceResponse(
    IEnumerable<PurchaseOrder> purchaseOrders
)
```

``` c++
public:
GetPurchaseOrderServiceResponse(
    IEnumerable<PurchaseOrder^>^ purchaseOrders
)
```

#### Parameters

  - purchaseOrders  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetPurchaseOrderServiceResponse Class](getpurchaseorderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

