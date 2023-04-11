---
title: ICustomerTriggerV2.PostCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV2.PostCustomer(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.icustomertriggerv2.postcustomer(v=AX.60)
ms:contentKeyID: 49821281
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV2.PostCustomer
dev_langs:
- CSharp
- C++
- VB
---

# PostCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered at the end

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostCustomer ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICustomerTriggerV2
Dim posTransaction As IPosTransaction

instance.PostCustomer(posTransaction)
```

``` csharp
void PostCustomer(
    IPosTransaction posTransaction
)
```

``` c++
void PostCustomer(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerTriggerV2 Interface](icustomertriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

