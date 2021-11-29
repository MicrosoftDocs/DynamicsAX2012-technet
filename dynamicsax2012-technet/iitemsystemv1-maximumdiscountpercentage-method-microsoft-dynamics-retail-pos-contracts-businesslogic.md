---
title: IItemSystemV1.MaximumDiscountPercentage Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: MaximumDiscountPercentage Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.MaximumDiscountPercentage(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv1.maximumdiscountpercentage(v=AX.60)
ms:contentKeyID: 47128491
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.MaximumDiscountPercentage
dev_langs:
- CSharp
- C++
- VB
---

# MaximumDiscountPercentage Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the maximum line discount percentage that a POS user can give.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function MaximumDiscountPercentage ( _
    staffId As String _
) As Decimal
'Usage
Dim instance As IItemSystemV1
Dim staffId As String
Dim returnValue As Decimal

returnValue = instance.MaximumDiscountPercentage(staffId)
```

``` csharp
decimal MaximumDiscountPercentage(
    string staffId
)
```

``` c++
Decimal MaximumDiscountPercentage(
    String^ staffId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns the maximum percentage discount that a POS user can give as a line discount.  

## See Also

#### Reference

[IItemSystemV1 Interface](iitemsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

