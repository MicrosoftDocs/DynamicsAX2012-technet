---
title: IPaymentTriggerV2.PreVoidPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreVoidPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV2.PreVoidPayment(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ipaymenttriggerv2.prevoidpayment(v=AX.60)
ms:contentKeyID: 49848214
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV2.PreVoidPayment
dev_langs:
- CSharp
- C++
- VB
---

# PreVoidPayment Method

Triggered before voiding of a payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreVoidPayment ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IPaymentTriggerV2
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PreVoidPayment(preTriggerResult, _
    posTransaction, lineId)
```

``` csharp
void PreVoidPayment(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PreVoidPayment(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IPaymentTriggerV2 Interface](ipaymenttriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

