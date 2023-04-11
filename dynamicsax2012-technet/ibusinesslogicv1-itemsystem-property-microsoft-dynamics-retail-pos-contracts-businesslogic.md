---
title: IBusinessLogicV1.ItemSystem Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ItemSystem Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogicV1.ItemSystem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.ibusinesslogicv1.itemsystem(v=AX.60)
ms:contentKeyID: 47128496
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogicV1.ItemSystem
dev_langs:
- CSharp
- C++
- VB
---

# ItemSystem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ItemSystem As IItemSystem
    Get
'Usage
Dim instance As IBusinessLogicV1
Dim value As IItemSystem

value = instance.ItemSystem
```

``` csharp
IItemSystem ItemSystem { get; }
```

``` c++
property IItemSystem^ ItemSystem {
    IItemSystem^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystem](iitemsystem-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)  
Returns [IItemSystem](iitemsystem-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md).  

## See Also

#### Reference

[IBusinessLogicV1 Interface](ibusinesslogicv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

