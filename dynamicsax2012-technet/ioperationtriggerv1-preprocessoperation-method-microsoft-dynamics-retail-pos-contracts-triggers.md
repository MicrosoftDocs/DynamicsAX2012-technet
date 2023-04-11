---
title: IOperationTriggerV1.PreProcessOperation Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreProcessOperation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IOperationTriggerV1.PreProcessOperation(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ioperationtriggerv1.preprocessoperation(v=AX.60)
ms:contentKeyID: 49827174
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IOperationTriggerV1.PreProcessOperation
dev_langs:
- CSharp
- C++
- VB
---

# PreProcessOperation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Before the operation is processed this trigger is called.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreProcessOperation ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    posisOperation As PosisOperations _
)
'Usage
Dim instance As IOperationTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim posisOperation As PosisOperations

instance.PreProcessOperation(preTriggerResult, _
    posTransaction, posisOperation)
```

``` csharp
void PreProcessOperation(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    PosisOperations posisOperation
)
```

``` c++
void PreProcessOperation(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    PosisOperations posisOperation
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posisOperation  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

## See Also

#### Reference

[IOperationTriggerV1 Interface](ioperationtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

