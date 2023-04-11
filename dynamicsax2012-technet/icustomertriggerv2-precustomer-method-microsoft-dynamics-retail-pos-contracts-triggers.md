---
title: ICustomerTriggerV2.PreCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV2.PreCustomer(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.icustomertriggerv2.precustomer(v=AX.60)
ms:contentKeyID: 49843094
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV2.PreCustomer
dev_langs:
- CSharp
- C++
- VB
---

# PreCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered at the beginning

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreCustomer ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICustomerTriggerV2
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction

instance.PreCustomer(preTriggerResult, _
    posTransaction)
```

``` csharp
void PreCustomer(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction
)
```

``` c++
void PreCustomer(
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

[ICustomerTriggerV2 Interface](icustomertriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

