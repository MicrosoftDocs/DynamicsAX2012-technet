---
title: ICustomerTriggerV1.PreCustomerClear Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreCustomerClear Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV1.PreCustomerClear(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.icustomertriggerv1.precustomerclear(v=AX.60)
ms:contentKeyID: 47128610
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV1.PreCustomerClear
dev_langs:
- CSharp
- C++
- VB
---

# PreCustomerClear Method

Triggered before a customer has been cleared from the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreCustomerClear ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICustomerTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction

instance.PreCustomerClear(preTriggerResult, _
    posTransaction)
```

``` csharp
void PreCustomerClear(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction
)
```

``` c++
void PreCustomerClear(
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

[ICustomerTriggerV1 Interface](icustomertriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

