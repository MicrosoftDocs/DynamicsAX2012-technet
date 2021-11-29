---
title: ButtonGridButton.Action Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Action Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.Action
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.action(v=AX.60)
ms:contentKeyID: 62213708
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.Action
dev_langs:
- CSharp
- C++
- VB
---

# Action Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the button action.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ACTION")> _
Public Property Action As Integer
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As Integer

value = instance.Action

instance.Action = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ACTION")]
public int Action { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ACTION")]
public:
property int Action {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The button action.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

