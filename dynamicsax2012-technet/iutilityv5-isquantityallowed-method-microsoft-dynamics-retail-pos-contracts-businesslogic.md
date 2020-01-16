---
title: IUtilityV5.IsQuantityAllowed Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: IsQuantityAllowed Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV5.IsQuantityAllowed(System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv5.isquantityallowed(v=AX.60)
ms:contentKeyID: 62203925
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV5.IsQuantityAllowed
dev_langs:
- CSharp
- C++
- VB
---

# IsQuantityAllowed Method

Verifies if the quantity is valid for the specified unit of measure.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsQuantityAllowed ( _
    quantity As Decimal, _
    unitId As String _
) As Boolean
'Usage
Dim instance As IUtilityV5
Dim quantity As Decimal
Dim unitId As String
Dim returnValue As Boolean

returnValue = instance.IsQuantityAllowed(quantity, _
    unitId)
```

``` csharp
bool IsQuantityAllowed(
    decimal quantity,
    string unitId
)
```

``` c++
bool IsQuantityAllowed(
    Decimal quantity, 
    String^ unitId
)
```

#### Parameters

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - unitId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if quantity is allowed for current unit of measure, false otherwise.  

## See Also

#### Reference

[IUtilityV5 Interface](iutilityv5-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

