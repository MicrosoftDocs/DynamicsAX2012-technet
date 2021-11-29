---
title: IItemTriggerV1.PostReturnItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostReturnItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostReturnItem(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1.postreturnitem(v=AX.60)
ms:contentKeyID: 47129024
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostReturnItem
dev_langs:
- CSharp
- C++
- VB
---

# PostReturnItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after an item is returned.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostReturnItem ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IItemTriggerV1
Dim posTransaction As IPosTransaction

instance.PostReturnItem(posTransaction)
```

``` csharp
void PostReturnItem(
    IPosTransaction posTransaction
)
```

``` c++
void PostReturnItem(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IItemTriggerV1 Interface](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

