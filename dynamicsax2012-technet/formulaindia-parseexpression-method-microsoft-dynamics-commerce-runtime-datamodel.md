---
title: FormulaIndia.ParseExpression Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ParseExpression Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.ParseExpression
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.formulaindia.parseexpression(v=AX.60)
ms:contentKeyID: 62205958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.ParseExpression
dev_langs:
- CSharp
- C++
- VB
---

# ParseExpression Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Parses the expression based on the delimiter above.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function ParseExpression As String()
'Usage
Dim instance As FormulaIndia
Dim returnValue As String()

returnValue = instance.ParseExpression()
```

``` csharp
public string[] ParseExpression()
```

``` c++
public:
array<String^>^ ParseExpression()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  
The calculation token.  

## See Also

#### Reference

[FormulaIndia Class](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

