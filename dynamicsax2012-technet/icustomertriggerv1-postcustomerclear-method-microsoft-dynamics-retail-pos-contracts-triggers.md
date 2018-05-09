---
title: ICustomerTriggerV1.PostCustomerClear Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostCustomerClear Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV1.PostCustomerClear(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.icustomertriggerv1.postcustomerclear(v=AX.60)
ms:contentKeyID: 47128473
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV1.PostCustomerClear
dev_langs:
- CSharp
- C++
- VB
---

# PostCustomerClear Method

Triggered after a customer has been cleared from the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostCustomerClear ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICustomerTriggerV1
Dim posTransaction As IPosTransaction

instance.PostCustomerClear(posTransaction)
```

``` csharp
void PostCustomerClear(
    IPosTransaction posTransaction
)
```

``` c++
void PostCustomerClear(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerTriggerV1 Interface](icustomertriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

