---
title: IItemSystemV1.RecalcPriceTaxDiscount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: RecalcPriceTaxDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.RecalcPriceTaxDiscount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv1.recalcpricetaxdiscount(v=AX.60)
ms:contentKeyID: 47128971
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.RecalcPriceTaxDiscount
dev_langs:
- CSharp
- C++
- VB
---

# RecalcPriceTaxDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Recalculates the price tax discount on the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub RecalcPriceTaxDiscount ( _
    transaction As IPosTransaction, _
    restoreItemPrices As Boolean _
)
'Usage
Dim instance As IItemSystemV1
Dim transaction As IPosTransaction
Dim restoreItemPrices As Boolean

instance.RecalcPriceTaxDiscount(transaction, _
    restoreItemPrices)
```

``` csharp
void RecalcPriceTaxDiscount(
    IPosTransaction transaction,
    bool restoreItemPrices
)
```

``` c++
void RecalcPriceTaxDiscount(
    IPosTransaction^ transaction, 
    bool restoreItemPrices
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - restoreItemPrices  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IItemSystemV1 Interface](iitemsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

