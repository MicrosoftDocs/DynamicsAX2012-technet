---
title: ButtonGridButton.BorderColorAsARGB Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BorderColorAsARGB Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.BorderColorAsARGB
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.bordercolorasargb(v=AX.60)
ms:contentKeyID: 62215129
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.BorderColorAsARGB
dev_langs:
- CSharp
- C++
- VB
---

# BorderColorAsARGB Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the button border color.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BORDERCOLOR", ManagedType := GetType(Integer))> _
Public Property BorderColorAsARGB As ARGBColor
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As ARGBColor

value = instance.BorderColorAsARGB

instance.BorderColorAsARGB = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BORDERCOLOR", ManagedType = typeof(int))]
public ARGBColor BorderColorAsARGB { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BORDERCOLOR", ManagedType = typeof(int))]
public:
property ARGBColor^ BorderColorAsARGB {
    ARGBColor^ get ();
    void set (ARGBColor^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ARGBColor](argbcolor-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The button border color.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

