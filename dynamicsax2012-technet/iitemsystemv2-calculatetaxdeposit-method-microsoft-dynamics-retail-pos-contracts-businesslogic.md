---
title: IItemSystemV2.CalculateTaxDeposit Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CalculateTaxDeposit Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV2.CalculateTaxDeposit(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv2.calculatetaxdeposit(v=AX.60)
ms:contentKeyID: 62205580
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV2.CalculateTaxDeposit
dev_langs:
- CSharp
- C++
- VB
---

# CalculateTaxDeposit Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculates tax deposit on a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateTaxDeposit ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IItemSystemV2
Dim transaction As IPosTransaction

instance.CalculateTaxDeposit(transaction)
```

``` csharp
void CalculateTaxDeposit(
    IPosTransaction transaction
)
```

``` c++
void CalculateTaxDeposit(
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

