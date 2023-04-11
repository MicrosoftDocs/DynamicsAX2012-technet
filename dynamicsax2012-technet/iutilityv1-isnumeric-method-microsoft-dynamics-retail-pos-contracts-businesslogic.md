---
title: IUtilityV1.IsNumeric Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: IsNumeric Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.IsNumeric(System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.isnumeric(v=AX.60)
ms:contentKeyID: 47128588
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.IsNumeric
dev_langs:
- CSharp
- C++
- VB
---

# IsNumeric Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Verifies if the expression is numeric.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsNumeric ( _
    expression As Object _
) As Boolean
'Usage
Dim instance As IUtilityV1
Dim expression As Object
Dim returnValue As Boolean

returnValue = instance.IsNumeric(expression)
```

``` csharp
bool IsNumeric(
    Object expression
)
```

``` c++
bool IsNumeric(
    Object^ expression
)
```

#### Parameters

  - expression  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns true if expression is numeric, or false otherwise.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

