---
title: IUtilityV1.ToBool Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ToBool Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.ToBool(System.Object)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.tobool(v=AX.60)
ms:contentKeyID: 47128761
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.ToBool
dev_langs:
- CSharp
- C++
- VB
---

# ToBool Method

Converts value to a boolean.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ToBool ( _
    value As Object _
) As Boolean
'Usage
Dim instance As IUtilityV1
Dim value As Object
Dim returnValue As Boolean

returnValue = instance.ToBool(value)
```

``` csharp
bool ToBool(
    Object value
)
```

``` c++
bool ToBool(
    Object^ value
)
```

#### Parameters

  - value  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if value is true or "1". False otherwise or if conversion fails.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

