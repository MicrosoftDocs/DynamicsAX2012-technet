---
title: ICashManagementTriggerV1.PreTenderDeclaration Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreTenderDeclaration Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICashManagementTriggerV1.PreTenderDeclaration(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.icashmanagementtriggerv1.pretenderdeclaration(v=AX.60)
ms:contentKeyID: 47128192
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICashManagementTriggerV1.PreTenderDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# PreTenderDeclaration Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered before the tender declaration operation has been run.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreTenderDeclaration ( _
    preTriggerResult As IPreTriggerResult, _
    transaction As IPosTransaction _
)
'Usage
Dim instance As ICashManagementTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim transaction As IPosTransaction

instance.PreTenderDeclaration(preTriggerResult, _
    transaction)
```

``` csharp
void PreTenderDeclaration(
    IPreTriggerResult preTriggerResult,
    IPosTransaction transaction
)
```

``` c++
void PreTenderDeclaration(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ transaction
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICashManagementTriggerV1 Interface](icashmanagementtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

