---
title: ICustomerTriggerV2.PostCustomerSearch Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostCustomerSearch Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV2.PostCustomerSearch(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.icustomertriggerv2.postcustomersearch(v=AX.60)
ms:contentKeyID: 49836735
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ICustomerTriggerV2.PostCustomerSearch
dev_langs:
- CSharp
- C++
- VB
---

# PostCustomerSearch Method

Triggered after customer search

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostCustomerSearch ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICustomerTriggerV2
Dim posTransaction As IPosTransaction

instance.PostCustomerSearch(posTransaction)
```

``` csharp
void PostCustomerSearch(
    IPosTransaction posTransaction
)
```

``` c++
void PostCustomerSearch(
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

