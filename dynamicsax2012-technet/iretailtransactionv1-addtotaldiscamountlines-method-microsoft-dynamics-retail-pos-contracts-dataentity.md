---
title: IRetailTransactionV1.AddTotalDiscAmountLines Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AddTotalDiscAmountLines Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.AddTotalDiscAmountLines(System.Type,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.addtotaldiscamountlines(v=AX.60)
ms:contentKeyID: 49834264
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.AddTotalDiscAmountLines
dev_langs:
- CSharp
- C++
- VB
---

# AddTotalDiscAmountLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This method will distribute the amountToDiscount across all the sale items in the transaction proportionally except for the line item with the largest amount. The remainder will be distributed to the line item with the largest amount to ensure the amount to discount is exactly applied.

This method currently works for either the customer discount or when the total discount button is applied

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddTotalDiscAmountLines ( _
    discountType As Type, _
    amountToDiscount As Decimal _
)
'Usage
Dim instance As IRetailTransactionV1
Dim discountType As Type
Dim amountToDiscount As Decimal

instance.AddTotalDiscAmountLines(discountType, _
    amountToDiscount)
```

``` csharp
void AddTotalDiscAmountLines(
    Type discountType,
    decimal amountToDiscount
)
```

``` c++
void AddTotalDiscAmountLines(
    Type^ discountType, 
    Decimal amountToDiscount
)
```

#### Parameters

  - discountType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

<!-- end list -->

  - amountToDiscount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

