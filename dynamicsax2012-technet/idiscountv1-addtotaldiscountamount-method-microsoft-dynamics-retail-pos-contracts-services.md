---
title: IDiscountV1.AddTotalDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddTotalDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddTotalDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.addtotaldiscountamount(v=AX.60)
ms:contentKeyID: 47344159
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddTotalDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# AddTotalDiscountAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Entry point for additional manipulation of the retail transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddTotalDiscountAmount ( _
    retailTransaction As IRetailTransaction, _
    amountValue As Decimal _
)
'Usage
Dim instance As IDiscountV1
Dim retailTransaction As IRetailTransaction
Dim amountValue As Decimal

instance.AddTotalDiscountAmount(retailTransaction, _
    amountValue)
```

``` csharp
void AddTotalDiscountAmount(
    IRetailTransaction retailTransaction,
    decimal amountValue
)
```

``` c++
void AddTotalDiscountAmount(
    IRetailTransaction^ retailTransaction, 
    Decimal amountValue
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - amountValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

