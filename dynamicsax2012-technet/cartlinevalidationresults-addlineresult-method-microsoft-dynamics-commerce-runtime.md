---
title: CartLineValidationResults.AddLineResult Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: AddLineResult Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.AddLineResult(System.Int32,Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartlinevalidationresults.addlineresult(v=AX.60)
ms:contentKeyID: 62214510
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.AddLineResult
dev_langs:
- CSharp
- C++
- VB
---

# AddLineResult Method

Adds a result for the given cart line index.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddLineResult ( _
    lineIndex As Integer, _
    result As DataValidationFailure _
)
'Usage
Dim instance As CartLineValidationResults
Dim lineIndex As Integer
Dim result As DataValidationFailure

instance.AddLineResult(lineIndex, result)
```

``` csharp
public void AddLineResult(
    int lineIndex,
    DataValidationFailure result
)
```

``` c++
public:
void AddLineResult(
    int lineIndex, 
    DataValidationFailure^ result
)
```

#### Parameters

  - lineIndex  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CartLineValidationResults Class](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

