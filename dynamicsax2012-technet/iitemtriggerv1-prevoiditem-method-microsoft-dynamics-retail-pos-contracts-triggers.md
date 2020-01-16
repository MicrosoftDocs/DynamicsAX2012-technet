---
title: IItemTriggerV1.PreVoidItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreVoidItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PreVoidItem(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1.prevoiditem(v=AX.60)
ms:contentKeyID: 47128119
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PreVoidItem
dev_langs:
- CSharp
- C++
- VB
---

# PreVoidItem Method

Triggered before an item is voided.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreVoidItem ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IItemTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PreVoidItem(preTriggerResult, _
    posTransaction, lineId)
```

``` csharp
void PreVoidItem(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PreVoidItem(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IItemTriggerV1 Interface](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

