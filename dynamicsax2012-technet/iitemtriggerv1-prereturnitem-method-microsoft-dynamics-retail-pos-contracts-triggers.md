---
title: IItemTriggerV1.PreReturnItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreReturnItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PreReturnItem(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1.prereturnitem(v=AX.60)
ms:contentKeyID: 47129227
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PreReturnItem
dev_langs:
- CSharp
- C++
- VB
---

# PreReturnItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered before an item is returned.

The return operation only sets the till to a "return state". It is the item sale operation that really returns the item (sells it with a negative quantity). Therefore, programming the "return triggers" only affects whether the till can enter the state when an item can be returned.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreReturnItem ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IItemTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction

instance.PreReturnItem(preTriggerResult, _
    posTransaction)
```

``` csharp
void PreReturnItem(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction
)
```

``` c++
void PreReturnItem(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IItemTriggerV1 Interface](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

