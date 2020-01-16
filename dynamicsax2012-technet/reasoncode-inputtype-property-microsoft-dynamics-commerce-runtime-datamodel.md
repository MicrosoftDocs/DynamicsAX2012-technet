---
title: ReasonCode.InputType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InputType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.InputType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.inputtype(v=AX.60)
ms:contentKeyID: 62202111
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.InputType
dev_langs:
- CSharp
- C++
- VB
---

# InputType Property

Gets the type of the input.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("INPUTTYPE")> _
Public Property InputType As ReasonCodeInputType
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As ReasonCodeInputType

value = instance.InputType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("INPUTTYPE")]
public ReasonCodeInputType InputType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"INPUTTYPE")]
public:
property ReasonCodeInputType InputType {
    ReasonCodeInputType get ();
    internal: void set (ReasonCodeInputType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputType](reasoncodeinputtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the input.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

