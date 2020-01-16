---
title: TaxCodeIndia.Formula Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: Formula Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.Formula
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeindia.formula(v=AX.60)
ms:contentKeyID: 62211436
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.Formula
dev_langs:
- CSharp
- C++
- VB
---

# Formula Property

Gets the formula.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Formula As FormulaIndia
    Get
'Usage
Dim instance As TaxCodeIndia
Dim value As FormulaIndia

value = instance.Formula
```

``` csharp
public FormulaIndia Formula { get; }
```

``` c++
public:
property FormulaIndia^ Formula {
    FormulaIndia^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [FormulaIndia](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TaxCodeIndia Class](taxcodeindia-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

