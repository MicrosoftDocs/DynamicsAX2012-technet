---
title: IDiscountItemV1.GetTotalDiscountAmountForSaleItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: GetTotalDiscountAmountForSaleItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItemV1.GetTotalDiscountAmountForSaleItem(System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.idiscountitemv1.gettotaldiscountamountforsaleitem(v=AX.60)
ms:contentKeyID: 49819681
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItemV1.GetTotalDiscountAmountForSaleItem
dev_langs:
- CSharp
- C++
- VB
---

# GetTotalDiscountAmountForSaleItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

For a given item price and quantity, find out what the total discounted amount would be

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetTotalDiscountAmountForSaleItem ( _
    itemPrice As Decimal, _
    itemQuantity As Decimal _
) As Decimal
'Usage
Dim instance As IDiscountItemV1
Dim itemPrice As Decimal
Dim itemQuantity As Decimal
Dim returnValue As Decimal

returnValue = instance.GetTotalDiscountAmountForSaleItem(itemPrice, _
    itemQuantity)
```

``` csharp
decimal GetTotalDiscountAmountForSaleItem(
    decimal itemPrice,
    decimal itemQuantity
)
```

``` c++
Decimal GetTotalDiscountAmountForSaleItem(
    Decimal itemPrice, 
    Decimal itemQuantity
)
```

#### Parameters

  - itemPrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - itemQuantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## Remarks

This is deprecated. See EffectiveAmount.

## See Also

#### Reference

[IDiscountItemV1 Interface](idiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

