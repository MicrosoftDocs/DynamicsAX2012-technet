---
title: ReasonCode.InputRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InputRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.InputRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.inputrequired(v=AX.60)
ms:contentKeyID: 62209026
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.InputRequired
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
<DataMemberAttribute> _
<ColumnAttribute("INPUTREQUIRED")> _
Public Property InputRequired As Boolean
    Get
    Set
'Usage
Dim instance As ReasonCode
Dim value As Boolean

value = instance.InputRequired

instance.InputRequired = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INPUTREQUIRED")]
public bool InputRequired { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INPUTREQUIRED")]
public:
property bool InputRequired {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if input is required; otherwise, false.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

