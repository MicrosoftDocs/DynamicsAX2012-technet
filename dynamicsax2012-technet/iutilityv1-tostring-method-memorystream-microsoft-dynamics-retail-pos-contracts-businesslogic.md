---
title: IUtilityV1.ToString Method (MemoryStream) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ToString Method (MemoryStream)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.ToString(System.IO.MemoryStream)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.tostring(v=AX.60)
ms:contentKeyID: 47128244
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ToString Method (MemoryStream)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts a memory stream to its string representation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ToString ( _
    stream As MemoryStream _
) As String
'Usage
Dim instance As IUtilityV1
Dim stream As MemoryStream
Dim returnValue As String

returnValue = instance.ToString(stream)
```

``` csharp
string ToString(
    MemoryStream stream
)
```

``` c++
String^ ToString(
    MemoryStream^ stream
)
```

#### Parameters

  - stream  
    Type: [System.IO.MemoryStream](https://technet.microsoft.com/library/9a84386f\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string value of the stream.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[ToString Overload](iutilityv1-tostring-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

