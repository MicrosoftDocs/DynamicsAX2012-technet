---
title: NumberSequenceSeedData.DataType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedData.DataType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.numbersequenceseeddata.datatype(v=AX.60)
ms:contentKeyID: 65319647
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedData.DataType
dev_langs:
- CSharp
- C++
- VB
---

# DataType Property

Gets or sets the type of the number sequence seed data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DATATYPE")> _
<IgnoreDataMemberAttribute> _
Public Property DataType As NumberSequenceSeedType
    Get
    Set
'Usage
Dim instance As NumberSequenceSeedData
Dim value As NumberSequenceSeedType

value = instance.DataType

instance.DataType = value
```

``` csharp
[ColumnAttribute("DATATYPE")]
[IgnoreDataMemberAttribute]
public NumberSequenceSeedType DataType { get; set; }
```

``` c++
[ColumnAttribute(L"DATATYPE")]
[IgnoreDataMemberAttribute]
public:
property NumberSequenceSeedType DataType {
    NumberSequenceSeedType get ();
    void set (NumberSequenceSeedType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[NumberSequenceSeedData Class](numbersequenceseeddata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

