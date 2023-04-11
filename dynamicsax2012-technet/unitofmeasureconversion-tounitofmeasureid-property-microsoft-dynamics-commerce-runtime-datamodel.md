---
title: UnitOfMeasureConversion.ToUnitOfMeasureId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToUnitOfMeasureId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.ToUnitOfMeasureId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.tounitofmeasureid(v=AX.60)
ms:contentKeyID: 62211301
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.ToUnitOfMeasureId
dev_langs:
- CSharp
- C++
- VB
---

# ToUnitOfMeasureId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit of measure to convert to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TOUNITID")> _
<ReadOnlyAttribute("TOUNITID")> _
Public Property ToUnitOfMeasureId As String
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As String

value = instance.ToUnitOfMeasureId

instance.ToUnitOfMeasureId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TOUNITID")]
[ReadOnlyAttribute("TOUNITID")]
public string ToUnitOfMeasureId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TOUNITID")]
[ReadOnlyAttribute(L"TOUNITID")]
public:
property String^ ToUnitOfMeasureId {
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

