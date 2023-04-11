---
title: IItemSystemV2.CalculatePriceDiscount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CalculatePriceDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV2.CalculatePriceDiscount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv2.calculatepricediscount(v=AX.60)
ms:contentKeyID: 62201745
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV2.CalculatePriceDiscount
dev_langs:
- CSharp
- C++
- VB
---

# CalculatePriceDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculates the price discount on a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculatePriceDiscount ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IItemSystemV2
Dim transaction As IPosTransaction

instance.CalculatePriceDiscount(transaction)
```

``` csharp
void CalculatePriceDiscount(
    IPosTransaction transaction
)
```

``` c++
void CalculatePriceDiscount(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IItemSystemV2 Interface](iitemsystemv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

