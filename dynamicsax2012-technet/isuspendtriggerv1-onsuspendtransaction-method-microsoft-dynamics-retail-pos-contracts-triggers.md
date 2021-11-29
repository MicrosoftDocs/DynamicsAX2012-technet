---
title: ISuspendTriggerV1.OnSuspendTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: OnSuspendTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ISuspendTriggerV1.OnSuspendTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.isuspendtriggerv1.onsuspendtransaction(v=AX.60)
ms:contentKeyID: 47129216
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ISuspendTriggerV1.OnSuspendTransaction
dev_langs:
- CSharp
- C++
- VB
---

# OnSuspendTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called when a transaction is suspended.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub OnSuspendTransaction ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ISuspendTriggerV1
Dim posTransaction As IPosTransaction

instance.OnSuspendTransaction(posTransaction)
```

``` csharp
void OnSuspendTransaction(
    IPosTransaction posTransaction
)
```

``` c++
void OnSuspendTransaction(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISuspendTriggerV1 Interface](isuspendtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

