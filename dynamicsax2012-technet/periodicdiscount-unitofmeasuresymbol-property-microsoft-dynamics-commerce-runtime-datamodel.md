---
title: PeriodicDiscount.UnitOfMeasureSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitOfMeasureSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.UnitOfMeasureSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.unitofmeasuresymbol(v=AX.60)
ms:contentKeyID: 49850209
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.UnitOfMeasureSymbol
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasureSymbol Property

Gets the unit of measure (if any) specified on this discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SYMBOL")> _
Public Property UnitOfMeasureSymbol As String
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As String

value = instance.UnitOfMeasureSymbol
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SYMBOL")]
public string UnitOfMeasureSymbol { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SYMBOL")]
public:
property String^ UnitOfMeasureSymbol {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

