---
title: IItemSystemV1.MaximumTotalDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: MaximumTotalDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.MaximumTotalDiscountAmount(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv1.maximumtotaldiscountamount(v=AX.60)
ms:contentKeyID: 47128775
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.MaximumTotalDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# MaximumTotalDiscountAmount Method

Returns the maximum line discount amount that a POS user can give.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function MaximumTotalDiscountAmount ( _
    staffId As String _
) As Decimal
'Usage
Dim instance As IItemSystemV1
Dim staffId As String
Dim returnValue As Decimal

returnValue = instance.MaximumTotalDiscountAmount(staffId)
```

``` csharp
decimal MaximumTotalDiscountAmount(
    string staffId
)
```

``` c++
Decimal MaximumTotalDiscountAmount(
    String^ staffId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns the maximum discount amount that a POS user can give as a line discount.  

## See Also

#### Reference

[IItemSystemV1 Interface](iitemsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

