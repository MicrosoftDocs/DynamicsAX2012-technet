---
title: ReasonCodeSpecific.InputRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InputRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.InputRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.inputrequired(v=AX.60)
ms:contentKeyID: 62209563
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.InputRequired
dev_langs:
- CSharp
- C++
- VB
---

# InputRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether input is required.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INPUTREQUIRED")> _
<DataMemberAttribute> _
Public Property InputRequired As Boolean
    Get
    Friend Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As Boolean

value = instance.InputRequired
```

``` csharp
[ColumnAttribute("INPUTREQUIRED")]
[DataMemberAttribute]
public bool InputRequired { get; internal set; }
```

``` c++
[ColumnAttribute(L"INPUTREQUIRED")]
[DataMemberAttribute]
public:
property bool InputRequired {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if input is required; otherwise, false.  

## See Also

#### Reference

[ReasonCodeSpecific Class](reasoncodespecific-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

