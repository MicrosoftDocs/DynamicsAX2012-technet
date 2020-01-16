---
title: IPaymentTriggerV1.PrePayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PrePayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV1.PrePayment(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Object,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ipaymenttriggerv1.prepayment(v=AX.60)
ms:contentKeyID: 47129017
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPaymentTriggerV1.PrePayment
dev_langs:
- CSharp
- C++
- VB
---

# PrePayment Method

Called for each payment operation, before an amount is set, any cards are swiped, any input is entered, or any dialogs are displayed.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrePayment ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    posOperation As Object, _
    tenderId As String _
)
'Usage
Dim instance As IPaymentTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim posOperation As Object
Dim tenderId As String

instance.PrePayment(preTriggerResult, _
    posTransaction, posOperation, tenderId)
```

``` csharp
void PrePayment(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    Object posOperation,
    string tenderId
)
```

``` c++
void PrePayment(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    Object^ posOperation, 
    String^ tenderId
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

## See Also

#### Reference

[IPaymentTriggerV1 Interface](ipaymenttriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

