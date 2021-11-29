---
title: ICustomerTriggerV2.PreCustomerSet Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreCustomerSet Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV2.PreCustomerSet(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.icustomertriggerv2.precustomerset(v=AX.60)
ms:contentKeyID: 49848219
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV2.PreCustomerSet
dev_langs:
- CSharp
- C++
- VB
---

# PreCustomerSet Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered just before the customer is set

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreCustomerSet ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    customerId As String _
)
'Usage
Dim instance As ICustomerTriggerV2
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim customerId As String

instance.PreCustomerSet(preTriggerResult, _
    posTransaction, customerId)
```

``` csharp
void PreCustomerSet(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    string customerId
)
```

``` c++
void PreCustomerSet(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    String^ customerId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICustomerTriggerV2 Interface](icustomertriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

