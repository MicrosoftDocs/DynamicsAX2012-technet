---
title: RoundingRule Delegate (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundingRule Delegate
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.roundingrule(v=AX.60)
ms:contentKeyID: 65321294
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule
dev_langs:
- CSharp
- C++
- VB
---

# RoundingRule Delegate

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Delegate Function RoundingRule ( _
    amountToRound As Decimal _
) As Decimal
'Usage
Dim instance As New RoundingRule(AddressOf HandlerMethod)
```

``` csharp
public delegate decimal RoundingRule(
    decimal amountToRound
)
```

``` c++
public delegate Decimal RoundingRule(
    Decimal amountToRound
)
```

#### Parameters

  - amountToRound  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

