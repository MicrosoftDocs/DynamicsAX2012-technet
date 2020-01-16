---
title: ButtonGridButton.ActionProperty Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ActionProperty Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.ActionProperty
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.actionproperty(v=AX.60)
ms:contentKeyID: 62206288
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.ActionProperty
dev_langs:
- CSharp
- C++
- VB
---

# ActionProperty Property

Gets or sets the button Action.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ACTIONPROPERTY")> _
Public Property ActionProperty As String
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As String

value = instance.ActionProperty

instance.ActionProperty = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ACTIONPROPERTY")]
public string ActionProperty { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ACTIONPROPERTY")]
public:
property String^ ActionProperty {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The button Action.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

