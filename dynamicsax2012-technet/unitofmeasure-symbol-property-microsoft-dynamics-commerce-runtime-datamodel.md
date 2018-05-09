---
title: UnitOfMeasure.Symbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Symbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasure.Symbol
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasure.symbol(v=AX.60)
ms:contentKeyID: 49840445
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasure.Symbol
dev_langs:
- CSharp
- C++
- VB
---

# Symbol Property

Gets the symbol for the unit of measure (e.g. "Pcs", "Cm", "Lbs").

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SYMBOL")> _
<DataMemberAttribute> _
<KeyAttribute> _
Public Property Symbol As String
    Get
    Set
'Usage
Dim instance As UnitOfMeasure
Dim value As String

value = instance.Symbol

instance.Symbol = value
```

``` csharp
[ColumnAttribute("SYMBOL")]
[DataMemberAttribute]
[KeyAttribute]
public string Symbol { get; set; }
```

``` c++
[ColumnAttribute(L"SYMBOL")]
[DataMemberAttribute]
[KeyAttribute]
public:
property String^ Symbol {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[UnitOfMeasure Class](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

