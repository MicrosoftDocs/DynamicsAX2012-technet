---
title: IInfocodeTriggerV1.PostProcessInfocode Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostProcessInfocode Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IInfocodeTriggerV1.PostProcessInfocode(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iinfocodetriggerv1.postprocessinfocode(v=AX.60)
ms:contentKeyID: 47129348
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IInfocodeTriggerV1.PostProcessInfocode
dev_langs:
- CSharp
- C++
- VB
---

# PostProcessInfocode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called after the infocode has been processed. Any checking and/or additional input validation can be done here.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostProcessInfocode ( _
    transaction As IPosTransaction, _
    tableRefId As InfoCodeTableRefType _
)
'Usage
Dim instance As IInfocodeTriggerV1
Dim transaction As IPosTransaction
Dim tableRefId As InfoCodeTableRefType

instance.PostProcessInfocode(transaction, _
    tableRefId)
```

``` csharp
void PostProcessInfocode(
    IPosTransaction transaction,
    InfoCodeTableRefType tableRefId
)
```

``` c++
void PostProcessInfocode(
    IPosTransaction^ transaction, 
    InfoCodeTableRefType tableRefId
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - tableRefId  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeTableRefType](infocodetablereftype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IInfocodeTriggerV1 Interface](iinfocodetriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

