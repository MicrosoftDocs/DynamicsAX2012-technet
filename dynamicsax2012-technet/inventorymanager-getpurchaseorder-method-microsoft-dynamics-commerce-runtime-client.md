---
title: InventoryManager.GetPurchaseOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetPurchaseOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetPurchaseOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getpurchaseorder(v=AX.60)
ms:contentKeyID: 62212263
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetPurchaseOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetPurchaseOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets open purchase orders from Ax or local database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetPurchaseOrder ( _
    orderId As String _
) As ReadOnlyCollection(Of PurchaseOrder)
'Usage
Dim instance As InventoryManager
Dim orderId As String
Dim returnValue As ReadOnlyCollection(Of PurchaseOrder)

returnValue = instance.GetPurchaseOrder(orderId)
```

``` csharp
public ReadOnlyCollection<PurchaseOrder> GetPurchaseOrder(
    string orderId
)
```

``` c++
public:
ReadOnlyCollection<PurchaseOrder^>^ GetPurchaseOrder(
    String^ orderId
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of purchase orders.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

