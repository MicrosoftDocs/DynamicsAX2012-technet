---
title: IItemSystemV1.MaximumDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: MaximumDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.MaximumDiscountAmount(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv1.maximumdiscountamount(v=AX.60)
ms:contentKeyID: 47128654
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.MaximumDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# MaximumDiscountAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the maximum line discount amount that a POS user can give.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function MaximumDiscountAmount ( _
    staffId As String _
) As Decimal
'Usage
Dim instance As IItemSystemV1
Dim staffId As String
Dim returnValue As Decimal

returnValue = instance.MaximumDiscountAmount(staffId)
```

``` csharp
decimal MaximumDiscountAmount(
    string staffId
)
```

``` c++
Decimal MaximumDiscountAmount(
    String^ staffId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns the maximum discount amount that a POS user can give as a line discount.  

## See Also

#### Reference

[IItemSystemV1 Interface](iitemsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

