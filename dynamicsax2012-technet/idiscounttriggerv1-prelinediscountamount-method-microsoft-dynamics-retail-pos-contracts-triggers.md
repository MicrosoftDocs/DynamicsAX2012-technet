---
title: IDiscountTriggerV1.PreLineDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreLineDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV1.PreLineDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.idiscounttriggerv1.prelinediscountamount(v=AX.60)
ms:contentKeyID: 47128789
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV1.PreLineDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# PreLineDiscountAmount Method

Triggered before the line discount amount is added.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreLineDiscountAmount ( _
    preTriggerResult As IPreTriggerResult, _
    transaction As IPosTransaction, _
    LineId As Integer _
)
'Usage
Dim instance As IDiscountTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim transaction As IPosTransaction
Dim LineId As Integer

instance.PreLineDiscountAmount(preTriggerResult, _
    transaction, LineId)
```

``` csharp
void PreLineDiscountAmount(
    IPreTriggerResult preTriggerResult,
    IPosTransaction transaction,
    int LineId
)
```

``` c++
void PreLineDiscountAmount(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ transaction, 
    int LineId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - LineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IDiscountTriggerV1 Interface](idiscounttriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

