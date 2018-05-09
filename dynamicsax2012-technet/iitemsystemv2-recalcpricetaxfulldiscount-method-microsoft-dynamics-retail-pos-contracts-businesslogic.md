---
title: IItemSystemV2.RecalcPriceTaxFullDiscount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: RecalcPriceTaxFullDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV2.RecalcPriceTaxFullDiscount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv2.recalcpricetaxfulldiscount(v=AX.60)
ms:contentKeyID: 62203327
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV2.RecalcPriceTaxFullDiscount
dev_langs:
- CSharp
- C++
- VB
---

# RecalcPriceTaxFullDiscount Method

Recalculates the price, full discount and tax on the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub RecalcPriceTaxFullDiscount ( _
    transaction As IPosTransaction, _
    restoreItemPrices As Boolean _
)
'Usage
Dim instance As IItemSystemV2
Dim transaction As IPosTransaction
Dim restoreItemPrices As Boolean

instance.RecalcPriceTaxFullDiscount(transaction, _
    restoreItemPrices)
```

``` csharp
void RecalcPriceTaxFullDiscount(
    IPosTransaction transaction,
    bool restoreItemPrices
)
```

``` c++
void RecalcPriceTaxFullDiscount(
    IPosTransaction^ transaction, 
    bool restoreItemPrices
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - restoreItemPrices  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IItemSystemV2 Interface](iitemsystemv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

