---
title: ReasonCodeLine.LineType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.LineType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.linetype(v=AX.60)
ms:contentKeyID: 62212529
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.LineType
dev_langs:
- CSharp
- C++
- VB
---

# LineType Property

Gets or sets the line type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TYPE")> _
Public Property LineType As ReasonCodeLineType
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As ReasonCodeLineType

value = instance.LineType

instance.LineType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TYPE")]
public ReasonCodeLineType LineType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TYPE")]
public:
property ReasonCodeLineType LineType {
    ReasonCodeLineType get ();
    void set (ReasonCodeLineType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLineType](reasoncodelinetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of line.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

