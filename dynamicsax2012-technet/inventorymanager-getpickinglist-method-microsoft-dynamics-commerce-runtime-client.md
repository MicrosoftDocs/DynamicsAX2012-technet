---
title: InventoryManager.GetPickingList Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetPickingList Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetPickingList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getpickinglist(v=AX.60)
ms:contentKeyID: 62207769
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetPickingList
dev_langs:
- CSharp
- C++
- VB
---

# GetPickingList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the picking lists from Ax or local database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetPickingList ( _
    orderId As String _
) As ReadOnlyCollection(Of PickingList)
'Usage
Dim instance As InventoryManager
Dim orderId As String
Dim returnValue As ReadOnlyCollection(Of PickingList)

returnValue = instance.GetPickingList(orderId)
```

``` csharp
public ReadOnlyCollection<PickingList> GetPickingList(
    string orderId
)
```

``` c++
public:
ReadOnlyCollection<PickingList^>^ GetPickingList(
    String^ orderId
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of picking lists.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

