---
title: IItemSystemV1.CalculatePriceTaxDiscount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CalculatePriceTaxDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.CalculatePriceTaxDiscount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv1.calculatepricetaxdiscount(v=AX.60)
ms:contentKeyID: 47129154
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.CalculatePriceTaxDiscount
dev_langs:
- CSharp
- C++
- VB
---

# CalculatePriceTaxDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculate and update the prices, then discounts, then taxes on a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculatePriceTaxDiscount ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IItemSystemV1
Dim transaction As IPosTransaction

instance.CalculatePriceTaxDiscount(transaction)
```

``` csharp
void CalculatePriceTaxDiscount(
    IPosTransaction transaction
)
```

``` c++
void CalculatePriceTaxDiscount(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IItemSystemV1 Interface](iitemsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

