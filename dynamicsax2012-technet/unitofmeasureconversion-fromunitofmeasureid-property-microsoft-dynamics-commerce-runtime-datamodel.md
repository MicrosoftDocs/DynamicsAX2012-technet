---
title: UnitOfMeasureConversion.FromUnitOfMeasureId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromUnitOfMeasureId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.FromUnitOfMeasureId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.fromunitofmeasureid(v=AX.60)
ms:contentKeyID: 62207897
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.FromUnitOfMeasureId
dev_langs:
- CSharp
- C++
- VB
---

# FromUnitOfMeasureId Property

Gets or sets the unit of measure to convert from.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FROMUNITID")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("FROMUNITID")> _
Public Property FromUnitOfMeasureId As String
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As String

value = instance.FromUnitOfMeasureId

instance.FromUnitOfMeasureId = value
```

``` csharp
[ColumnAttribute("FROMUNITID")]
[DataMemberAttribute]
[ReadOnlyAttribute("FROMUNITID")]
public string FromUnitOfMeasureId { get; set; }
```

``` c++
[ColumnAttribute(L"FROMUNITID")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"FROMUNITID")]
public:
property String^ FromUnitOfMeasureId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

