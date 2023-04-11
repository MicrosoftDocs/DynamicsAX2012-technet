---
title: IOperationTriggerV1.PostProcessOperation Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostProcessOperation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IOperationTriggerV1.PostProcessOperation(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ioperationtriggerv1.postprocessoperation(v=AX.60)
ms:contentKeyID: 49848670
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IOperationTriggerV1.PostProcessOperation
dev_langs:
- CSharp
- C++
- VB
---

# PostProcessOperation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

After the operation has been processed this trigger is called.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostProcessOperation ( _
    posTransaction As IPosTransaction, _
    posisOperation As PosisOperations _
)
'Usage
Dim instance As IOperationTriggerV1
Dim posTransaction As IPosTransaction
Dim posisOperation As PosisOperations

instance.PostProcessOperation(posTransaction, _
    posisOperation)
```

``` csharp
void PostProcessOperation(
    IPosTransaction posTransaction,
    PosisOperations posisOperation
)
```

``` c++
void PostProcessOperation(
    IPosTransaction^ posTransaction, 
    PosisOperations posisOperation
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posisOperation  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

## See Also

#### Reference

[IOperationTriggerV1 Interface](ioperationtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

