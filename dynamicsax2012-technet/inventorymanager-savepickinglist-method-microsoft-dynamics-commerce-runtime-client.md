---
title: InventoryManager.SavePickingList Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SavePickingList Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SavePickingList(System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.savepickinglist(v=AX.60)
ms:contentKeyID: 62202560
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SavePickingList
dev_langs:
- CSharp
- C++
- VB
---

# SavePickingList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Saves the count of a picking list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub SavePickingList ( _
    commit As Boolean, _
    pickingList As PickingList _
)
'Usage
Dim instance As InventoryManager
Dim commit As Boolean
Dim pickingList As PickingList

instance.SavePickingList(commit, pickingList)
```

``` csharp
public void SavePickingList(
    bool commit,
    PickingList pickingList
)
```

``` c++
public:
void SavePickingList(
    bool commit, 
    PickingList^ pickingList
)
```

#### Parameters

  - commit  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - pickingList  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

