---
title: UnitOfMeasureConversion.OuterOffset Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OuterOffset Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.OuterOffset
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.outeroffset(v=AX.60)
ms:contentKeyID: 49843052
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.OuterOffset
dev_langs:
- CSharp
- C++
- VB
---

# OuterOffset Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the outer offset.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OUTEROFFSET")> _
<ReadOnlyAttribute("OUTEROFFSET")> _
Public Property OuterOffset As Decimal
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As Decimal

value = instance.OuterOffset

instance.OuterOffset = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OUTEROFFSET")]
[ReadOnlyAttribute("OUTEROFFSET")]
public decimal OuterOffset { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OUTEROFFSET")]
[ReadOnlyAttribute(L"OUTEROFFSET")]
public:
property Decimal OuterOffset {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The outer offset.  

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

