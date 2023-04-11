---
title: InventoryManager.SaveKitTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SaveKitTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SaveKitTransaction(Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.savekittransaction(v=AX.60)
ms:contentKeyID: 62215003
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SaveKitTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SaveKitTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Saves the kit (disassembly) transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SaveKitTransaction ( _
    transaction As KitTransaction _
) As KitTransaction
'Usage
Dim instance As InventoryManager
Dim transaction As KitTransaction
Dim returnValue As KitTransaction

returnValue = instance.SaveKitTransaction(transaction)
```

``` csharp
public KitTransaction SaveKitTransaction(
    KitTransaction transaction
)
```

``` c++
public:
KitTransaction^ SaveKitTransaction(
    KitTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransaction](kittransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransaction](kittransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the kit transaction object.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

