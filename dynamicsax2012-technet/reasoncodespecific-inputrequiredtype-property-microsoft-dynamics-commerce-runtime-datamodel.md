---
title: ReasonCodeSpecific.InputRequiredType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InputRequiredType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.InputRequiredType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.inputrequiredtype(v=AX.60)
ms:contentKeyID: 62210920
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.InputRequiredType
dev_langs:
- CSharp
- C++
- VB
---

# InputRequiredType Property

Gets the input required type of the reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("WHENREQUIRED")> _
Public Property InputRequiredType As ReasonCodeInputRequiredType
    Get
    Friend Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As ReasonCodeInputRequiredType

value = instance.InputRequiredType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("WHENREQUIRED")]
public ReasonCodeInputRequiredType InputRequiredType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"WHENREQUIRED")]
public:
property ReasonCodeInputRequiredType InputRequiredType {
    ReasonCodeInputRequiredType get ();
    internal: void set (ReasonCodeInputRequiredType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputRequiredType](reasoncodeinputrequiredtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The input required type value.  

## See Also

#### Reference

[ReasonCodeSpecific Class](reasoncodespecific-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

