---
title: UnitOfMeasureConversion.ToUnitOfMeasureSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToUnitOfMeasureSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.ToUnitOfMeasureSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.tounitofmeasuresymbol(v=AX.60)
ms:contentKeyID: 62209849
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.ToUnitOfMeasureSymbol
dev_langs:
- CSharp
- C++
- VB
---

# ToUnitOfMeasureSymbol Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit of measure symbol to convert to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOUOMSYMBOL")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("TOUOMSYMBOL")> _
Public Property ToUnitOfMeasureSymbol As String
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As String

value = instance.ToUnitOfMeasureSymbol

instance.ToUnitOfMeasureSymbol = value
```

``` csharp
[ColumnAttribute("TOUOMSYMBOL")]
[DataMemberAttribute]
[ReadOnlyAttribute("TOUOMSYMBOL")]
public string ToUnitOfMeasureSymbol { get; set; }
```

``` c++
[ColumnAttribute(L"TOUOMSYMBOL")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"TOUOMSYMBOL")]
public:
property String^ ToUnitOfMeasureSymbol {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

