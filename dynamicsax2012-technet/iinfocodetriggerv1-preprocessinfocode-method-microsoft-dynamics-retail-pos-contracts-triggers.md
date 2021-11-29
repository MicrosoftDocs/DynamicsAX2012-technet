---
title: IInfocodeTriggerV1.PreProcessInfocode Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreProcessInfocode Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IInfocodeTriggerV1.PreProcessInfocode(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iinfocodetriggerv1.preprocessinfocode(v=AX.60)
ms:contentKeyID: 47129318
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IInfocodeTriggerV1.PreProcessInfocode
dev_langs:
- CSharp
- C++
- VB
---

# PreProcessInfocode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called before the infocode is processed. If the infocode should not be processed after this trigger has finished running, PreTriggerResults must to be filled out accordingly.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreProcessInfocode ( _
    preTriggerResult As IPreTriggerResult, _
    transaction As IPosTransaction, _
    tableRefId As InfoCodeTableRefType _
)
'Usage
Dim instance As IInfocodeTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim transaction As IPosTransaction
Dim tableRefId As InfoCodeTableRefType

instance.PreProcessInfocode(preTriggerResult, _
    transaction, tableRefId)
```

``` csharp
void PreProcessInfocode(
    IPreTriggerResult preTriggerResult,
    IPosTransaction transaction,
    InfoCodeTableRefType tableRefId
)
```

``` c++
void PreProcessInfocode(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ transaction, 
    InfoCodeTableRefType tableRefId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - tableRefId  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType](infocodetablereftype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IInfocodeTriggerV1 Interface](iinfocodetriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

