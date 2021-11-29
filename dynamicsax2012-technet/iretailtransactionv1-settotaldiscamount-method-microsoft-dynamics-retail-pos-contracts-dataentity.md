---
title: IRetailTransactionV1.SetTotalDiscAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SetTotalDiscAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.SetTotalDiscAmount(System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.settotaldiscamount(v=AX.60)
ms:contentKeyID: 49829180
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.SetTotalDiscAmount
dev_langs:
- CSharp
- C++
- VB
---

# SetTotalDiscAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Set the amount given as a total discount for the transaction

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SetTotalDiscAmount ( _
    totalDiscountAmount As Decimal _
)
'Usage
Dim instance As IRetailTransactionV1
Dim totalDiscountAmount As Decimal

instance.SetTotalDiscAmount(totalDiscountAmount)
```

``` csharp
void SetTotalDiscAmount(
    decimal totalDiscountAmount
)
```

``` c++
void SetTotalDiscAmount(
    Decimal totalDiscountAmount
)
```

#### Parameters

  - totalDiscountAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

