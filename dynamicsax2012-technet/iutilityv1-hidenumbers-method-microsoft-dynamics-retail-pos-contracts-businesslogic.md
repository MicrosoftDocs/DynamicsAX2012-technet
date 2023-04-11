---
title: IUtilityV1.HideNumbers Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: HideNumbers Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.HideNumbers(System.String,System.Char)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.hidenumbers(v=AX.60)
ms:contentKeyID: 47128871
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.HideNumbers
dev_langs:
- CSharp
- C++
- VB
---

# HideNumbers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Replaces numbers on trackString by replacementToken.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function HideNumbers ( _
    trackString As String, _
    replacementToken As Char _
) As String
'Usage
Dim instance As IUtilityV1
Dim trackString As String
Dim replacementToken As Char
Dim returnValue As String

returnValue = instance.HideNumbers(trackString, _
    replacementToken)
```

``` csharp
string HideNumbers(
    string trackString,
    char replacementToken
)
```

``` c++
String^ HideNumbers(
    String^ trackString, 
    wchar_t replacementToken
)
```

#### Parameters

  - trackString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - replacementToken  
    Type: [System.Char](https://technet.microsoft.com/library/k493b04s\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The transformed string.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

