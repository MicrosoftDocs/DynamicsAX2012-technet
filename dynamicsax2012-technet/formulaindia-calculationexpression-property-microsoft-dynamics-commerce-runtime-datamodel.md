---
title: FormulaIndia.CalculationExpression Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CalculationExpression Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.CalculationExpression
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.formulaindia.calculationexpression(v=AX.60)
ms:contentKeyID: 62208774
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.CalculationExpression
dev_langs:
- CSharp
- C++
- VB
---

# CalculationExpression Property

Gets the calculation expression of the tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CALCEXP1")> _
Public Property CalculationExpression As String
    Get
    Friend Set
'Usage
Dim instance As FormulaIndia
Dim value As String

value = instance.CalculationExpression
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CALCEXP1")]
public string CalculationExpression { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CALCEXP1")]
public:
property String^ CalculationExpression {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Of the form expression: +\[BCD\]+\[CVD\]+\[E-CESS\_CVD\]+\[PE-C\_CVD\]+\[SHE-C\_CVD\] where the brackets are replaced with the delimiter char(164) and BCD, CVD ... are tax codes.

The operator may be + - / \*.

## See Also

#### Reference

[FormulaIndia Class](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

