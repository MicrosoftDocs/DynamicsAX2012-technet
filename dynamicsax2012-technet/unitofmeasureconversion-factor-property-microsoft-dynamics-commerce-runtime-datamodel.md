---
title: UnitOfMeasureConversion.Factor Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Factor Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.Factor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.factor(v=AX.60)
ms:contentKeyID: 49823558
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.Factor
dev_langs:
- CSharp
- C++
- VB
---

# Factor Property

Gets or sets the factor.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FACTOR")> _
<ReadOnlyAttribute("FACTOR")> _
<DataMemberAttribute> _
Public Property Factor As Decimal
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As Decimal

value = instance.Factor

instance.Factor = value
```

``` csharp
[ColumnAttribute("FACTOR")]
[ReadOnlyAttribute("FACTOR")]
[DataMemberAttribute]
public decimal Factor { get; set; }
```

``` c++
[ColumnAttribute(L"FACTOR")]
[ReadOnlyAttribute(L"FACTOR")]
[DataMemberAttribute]
public:
property Decimal Factor {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The factor.  

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

