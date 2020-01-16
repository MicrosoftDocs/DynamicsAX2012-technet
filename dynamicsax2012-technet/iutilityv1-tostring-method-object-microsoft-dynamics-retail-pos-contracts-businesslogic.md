---
title: IUtilityV1.ToString Method (Object) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ToString Method (Object)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.ToString(System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.tostring(v=AX.60)
ms:contentKeyID: 47128371
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ToString Method (Object)

Converts value to a string.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ToString ( _
    value As Object _
) As String
'Usage
Dim instance As IUtilityV1
Dim value As Object
Dim returnValue As String

returnValue = instance.ToString(value)
```

``` csharp
string ToString(
    Object value
)
```

``` c++
String^ ToString(
    Object^ value
)
```

#### Parameters

  - value  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string value or an empty string if conversion fails.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[ToString Overload](iutilityv1-tostring-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

