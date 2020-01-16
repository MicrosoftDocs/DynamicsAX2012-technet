---
title: IPaymentTriggerV1.OnPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: OnPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV1.OnPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ipaymenttriggerv1.onpayment(v=AX.60)
ms:contentKeyID: 47128423
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV1.OnPayment
dev_langs:
- CSharp
- C++
- VB
---

# OnPayment Method

Called when the payment has been added to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub OnPayment ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IPaymentTriggerV1
Dim posTransaction As IPosTransaction

instance.OnPayment(posTransaction)
```

``` csharp
void OnPayment(
    IPosTransaction posTransaction
)
```

``` c++
void OnPayment(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IPaymentTriggerV1 Interface](ipaymenttriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

