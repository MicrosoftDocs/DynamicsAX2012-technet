---
title: IPaymentTriggerV3.PreRegisterPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreRegisterPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV3.PreRegisterPayment(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Object,System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ipaymenttriggerv3.preregisterpayment(v=AX.60)
ms:contentKeyID: 62202970
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV3.PreRegisterPayment
dev_langs:
- CSharp
- C++
- VB
---

# PreRegisterPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered before registering a payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreRegisterPayment ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    posOperation As Object, _
    tenderId As String, _
    currencyCode As String, _
    amount As Decimal _
)
'Usage
Dim instance As IPaymentTriggerV3
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim posOperation As Object
Dim tenderId As String
Dim currencyCode As String
Dim amount As Decimal

instance.PreRegisterPayment(preTriggerResult, _
    posTransaction, posOperation, tenderId, _
    currencyCode, amount)
```

``` csharp
void PreRegisterPayment(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    Object posOperation,
    string tenderId,
    string currencyCode,
    decimal amount
)
```

``` c++
void PreRegisterPayment(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    Object^ posOperation, 
    String^ tenderId, 
    String^ currencyCode, 
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

  - posOperation  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - tenderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## Remarks

This trigger is fired at the point in time when we know the amount of the payment, but before the payment is registered.

## See Also

#### Reference

[IPaymentTriggerV3 Interface](ipaymenttriggerv3-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

