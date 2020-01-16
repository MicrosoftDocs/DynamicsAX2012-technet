---
title: ITriggersV1.PaymentTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PaymentTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.PaymentTriggers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv1.paymenttriggers(v=AX.60)
ms:contentKeyID: 47129342
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.PaymentTriggers
dev_langs:
- CSharp
- C++
- VB
---

# PaymentTriggers Property

Gets the payment triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property PaymentTriggers As IEnumerable(Of IPaymentTrigger)
    Get
'Usage
Dim instance As ITriggersV1
Dim value As IEnumerable(Of IPaymentTrigger)

value = instance.PaymentTriggers
```

``` csharp
IEnumerable<IPaymentTrigger> PaymentTriggers { get; }
```

``` c++
property IEnumerable<IPaymentTrigger^>^ PaymentTriggers {
    IEnumerable<IPaymentTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[IPaymentTrigger](ipaymenttrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
The [System.Collections.Generic.IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV1 Interface](itriggersv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

