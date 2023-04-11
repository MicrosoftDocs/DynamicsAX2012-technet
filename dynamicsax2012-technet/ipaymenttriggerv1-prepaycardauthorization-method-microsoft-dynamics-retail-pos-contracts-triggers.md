---
title: IPaymentTriggerV1.PrePayCardAuthorization Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PrePayCardAuthorization Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV1.PrePayCardAuthorization(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ipaymenttriggerv1.prepaycardauthorization(v=AX.60)
ms:contentKeyID: 47129220
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV1.PrePayCardAuthorization
dev_langs:
- CSharp
- C++
- VB
---

# PrePayCardAuthorization Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called before the pay card authorization is made.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrePayCardAuthorization ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    cardInfo As ICardInfo, _
    amount As Decimal _
)
'Usage
Dim instance As IPaymentTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim cardInfo As ICardInfo
Dim amount As Decimal

instance.PrePayCardAuthorization(preTriggerResult, _
    posTransaction, cardInfo, amount)
```

``` csharp
void PrePayCardAuthorization(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    ICardInfo cardInfo,
    decimal amount
)
```

``` c++
void PrePayCardAuthorization(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    ICardInfo^ cardInfo, 
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

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[IPaymentTriggerV1 Interface](ipaymenttriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

