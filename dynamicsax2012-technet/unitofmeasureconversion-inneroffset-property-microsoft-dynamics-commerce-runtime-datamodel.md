---
title: UnitOfMeasureConversion.InnerOffset Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InnerOffset Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.InnerOffset
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.inneroffset(v=AX.60)
ms:contentKeyID: 49840722
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.InnerOffset
dev_langs:
- CSharp
- C++
- VB
---

# InnerOffset Property

Gets or sets the inner offset.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("INNEROFFSET")> _
<ColumnAttribute("INNEROFFSET")> _
Public Property InnerOffset As Decimal
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As Decimal

value = instance.InnerOffset

instance.InnerOffset = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("INNEROFFSET")]
[ColumnAttribute("INNEROFFSET")]
public decimal InnerOffset { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"INNEROFFSET")]
[ColumnAttribute(L"INNEROFFSET")]
public:
property Decimal InnerOffset {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The inner offset.  

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

