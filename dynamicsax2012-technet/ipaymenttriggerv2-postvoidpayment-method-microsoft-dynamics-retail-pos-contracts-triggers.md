---
title: IPaymentTriggerV2.PostVoidPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostVoidPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV2.PostVoidPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ipaymenttriggerv2.postvoidpayment(v=AX.60)
ms:contentKeyID: 49820836
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV2.PostVoidPayment
dev_langs:
- CSharp
- C++
- VB
---

# PostVoidPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after voiding of a payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostVoidPayment ( _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IPaymentTriggerV2
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PostVoidPayment(posTransaction, _
    lineId)
```

``` csharp
void PostVoidPayment(
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PostVoidPayment(
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IPaymentTriggerV2 Interface](ipaymenttriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

