---
title: GetPurchaseOrderResponse Constructor (IEnumerable(PurchaseOrder)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetPurchaseOrderResponse Constructor (IEnumerable(PurchaseOrder))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetPurchaseOrderResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getpurchaseorderresponse.getpurchaseorderresponse(v=AX.60)
ms:contentKeyID: 62209529
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetPurchaseOrderResponse Constructor (IEnumerable(PurchaseOrder))

Initializes a new instance of the [GetPurchaseOrderResponse](getpurchaseorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    purchaseOrders As IEnumerable(Of PurchaseOrder) _
)
'Usage
Dim purchaseOrders As IEnumerable(Of PurchaseOrder)

Dim instance As New GetPurchaseOrderResponse(purchaseOrders)
```

``` csharp
public GetPurchaseOrderResponse(
    IEnumerable<PurchaseOrder> purchaseOrders
)
```

``` c++
public:
GetPurchaseOrderResponse(
    IEnumerable<PurchaseOrder^>^ purchaseOrders
)
```

#### Parameters

  - purchaseOrders  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetPurchaseOrderResponse Class](getpurchaseorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetPurchaseOrderResponse Overload](getpurchaseorderresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

