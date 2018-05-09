---
title: InventoryManager.GetTransferOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetTransferOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetTransferOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.gettransferorder(v=AX.60)
ms:contentKeyID: 62211827
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetTransferOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetTransferOrder Method

Gets the transfer orders from Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransferOrder ( _
    orderId As String _
) As ReadOnlyCollection(Of TransferOrder)
'Usage
Dim instance As InventoryManager
Dim orderId As String
Dim returnValue As ReadOnlyCollection(Of TransferOrder)

returnValue = instance.GetTransferOrder(orderId)
```

``` csharp
public ReadOnlyCollection<TransferOrder> GetTransferOrder(
    string orderId
)
```

``` c++
public:
ReadOnlyCollection<TransferOrder^>^ GetTransferOrder(
    String^ orderId
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of transfer orders.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

