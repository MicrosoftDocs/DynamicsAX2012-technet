---
title: InventoryManager.SavePickReceiveCount Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SavePickReceiveCount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SavePickReceiveCount(System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder,Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.savepickreceivecount(v=AX.60)
ms:contentKeyID: 62208219
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SavePickReceiveCount
dev_langs:
- CSharp
- C++
- VB
---

# SavePickReceiveCount Method

Saves the count of a purchase or a transfer order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub SavePickReceiveCount ( _
    commit As Boolean, _
    purchaseOrder As PurchaseOrder, _
    transferOrder As TransferOrder _
)
'Usage
Dim instance As InventoryManager
Dim commit As Boolean
Dim purchaseOrder As PurchaseOrder
Dim transferOrder As TransferOrder

instance.SavePickReceiveCount(commit, _
    purchaseOrder, transferOrder)
```

``` csharp
public void SavePickReceiveCount(
    bool commit,
    PurchaseOrder purchaseOrder,
    TransferOrder transferOrder
)
```

``` c++
public:
void SavePickReceiveCount(
    bool commit, 
    PurchaseOrder^ purchaseOrder, 
    TransferOrder^ transferOrder
)
```

#### Parameters

  - commit  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - purchaseOrder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - transferOrder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

