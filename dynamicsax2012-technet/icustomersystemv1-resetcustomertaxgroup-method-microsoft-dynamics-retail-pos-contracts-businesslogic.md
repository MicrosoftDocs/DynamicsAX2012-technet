---
title: ICustomerSystemV1.ResetCustomerTaxGroup Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ResetCustomerTaxGroup Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.ResetCustomerTaxGroup(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv1.resetcustomertaxgroup(v=AX.60)
ms:contentKeyID: 47128660
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.ResetCustomerTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# ResetCustomerTaxGroup Method

Update the line items and charges to reflect the accurate sales tax group.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ResetCustomerTaxGroup ( _
    taxableItem As ITaxableItem _
)
'Usage
Dim instance As ICustomerSystemV1
Dim taxableItem As ITaxableItem

instance.ResetCustomerTaxGroup(taxableItem)
```

``` csharp
void ResetCustomerTaxGroup(
    ITaxableItem taxableItem
)
```

``` c++
void ResetCustomerTaxGroup(
    ITaxableItem^ taxableItem
)
```

#### Parameters

  - taxableItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerSystemV1 Interface](icustomersystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

