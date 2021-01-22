---
title: ButtonGridButton.FontColorAsARGB Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FontColorAsARGB Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.FontColorAsARGB
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.fontcolorasargb(v=AX.60)
ms:contentKeyID: 62212148
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.FontColorAsARGB
dev_langs:
- CSharp
- C++
- VB
---

# FontColorAsARGB Property

Gets or sets the button's font color.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FONTCOLOR", ManagedType := GetType(Integer))> _
Public Property FontColorAsARGB As ARGBColor
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As ARGBColor

value = instance.FontColorAsARGB

instance.FontColorAsARGB = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FONTCOLOR", ManagedType = typeof(int))]
public ARGBColor FontColorAsARGB { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FONTCOLOR", ManagedType = typeof(int))]
public:
property ARGBColor^ FontColorAsARGB {
    ARGBColor^ get ();
    void set (ARGBColor^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ARGBColor](argbcolor-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The button's font color.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

