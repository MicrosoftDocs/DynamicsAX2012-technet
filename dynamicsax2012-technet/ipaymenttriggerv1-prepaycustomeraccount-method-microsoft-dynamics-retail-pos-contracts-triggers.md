---
title: IPaymentTriggerV1.PrePayCustomerAccount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PrePayCustomerAccount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV1.PrePayCustomerAccount(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ipaymenttriggerv1.prepaycustomeraccount(v=AX.60)
ms:contentKeyID: 47128495
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV1.PrePayCustomerAccount
dev_langs:
- CSharp
- C++
- VB
---

# PrePayCustomerAccount Method

Called before a customer account payment is made.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrePayCustomerAccount ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    amount As Decimal _
)
'Usage
Dim instance As IPaymentTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim amount As Decimal

instance.PrePayCustomerAccount(preTriggerResult, _
    posTransaction, amount)
```

``` csharp
void PrePayCustomerAccount(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    decimal amount
)
```

``` c++
void PrePayCustomerAccount(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    Decimal amount
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[IPaymentTriggerV1 Interface](ipaymenttriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

