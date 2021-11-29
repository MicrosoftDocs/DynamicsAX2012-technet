---
title: IItemSystemV1.MaximumTotalDiscountPercentage Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: MaximumTotalDiscountPercentage Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.MaximumTotalDiscountPercentage(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv1.maximumtotaldiscountpercentage(v=AX.60)
ms:contentKeyID: 47129341
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.MaximumTotalDiscountPercentage
dev_langs:
- CSharp
- C++
- VB
---

# MaximumTotalDiscountPercentage Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the maximum total discount that a POS user can give.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function MaximumTotalDiscountPercentage ( _
    staffId As String _
) As Decimal
'Usage
Dim instance As IItemSystemV1
Dim staffId As String
Dim returnValue As Decimal

returnValue = instance.MaximumTotalDiscountPercentage(staffId)
```

``` csharp
decimal MaximumTotalDiscountPercentage(
    string staffId
)
```

``` c++
Decimal MaximumTotalDiscountPercentage(
    String^ staffId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns the maximum percentage discount that a POS user can give as a total discount.  

## See Also

#### Reference

[IItemSystemV1 Interface](iitemsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

