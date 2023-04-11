---
title: ReasonCodeLine.InputType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InputType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.InputType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.inputtype(v=AX.60)
ms:contentKeyID: 62211569
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.InputType
dev_langs:
- CSharp
- C++
- VB
---

# InputType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the input.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INPUTTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property InputType As ReasonCodeInputType
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As ReasonCodeInputType

value = instance.InputType

instance.InputType = value
```

``` csharp
[ColumnAttribute("INPUTTYPE")]
[IgnoreDataMemberAttribute]
public ReasonCodeInputType InputType { get; set; }
```

``` c++
[ColumnAttribute(L"INPUTTYPE")]
[IgnoreDataMemberAttribute]
public:
property ReasonCodeInputType InputType {
    ReasonCodeInputType get ();
    void set (ReasonCodeInputType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputType](reasoncodeinputtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the input.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

