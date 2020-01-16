---
title: ItemAvailability.UnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.UnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailability.unitofmeasure(v=AX.60)
ms:contentKeyID: 49849076
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.UnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasure Property

Gets or sets the unit of measure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("UNITID")> _
Public Property UnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As ItemAvailability
Dim value As String

value = instance.UnitOfMeasure

instance.UnitOfMeasure = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("UNITID")]
public string UnitOfMeasure { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"UNITID")]
public:
property String^ UnitOfMeasure {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemAvailability Class](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

