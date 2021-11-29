---
title: ICashManagementTriggerV1.PostTenderDeclaration Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostTenderDeclaration Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICashManagementTriggerV1.PostTenderDeclaration(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.icashmanagementtriggerv1.posttenderdeclaration(v=AX.60)
ms:contentKeyID: 47128486
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICashManagementTriggerV1.PostTenderDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# PostTenderDeclaration Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after the tender declaration operation has run.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostTenderDeclaration ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As ICashManagementTriggerV1
Dim transaction As IPosTransaction

instance.PostTenderDeclaration(transaction)
```

``` csharp
void PostTenderDeclaration(
    IPosTransaction transaction
)
```

``` c++
void PostTenderDeclaration(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICashManagementTriggerV1 Interface](icashmanagementtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

