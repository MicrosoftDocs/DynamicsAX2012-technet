---
title: ButtonGridButton.BackColorAsARGB Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BackColorAsARGB Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.BackColorAsARGB
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.backcolorasargb(v=AX.60)
ms:contentKeyID: 62208302
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.BackColorAsARGB
dev_langs:
- CSharp
- C++
- VB
---

# BackColorAsARGB Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the button backcolor.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BACKCOLOR", ManagedType := GetType(Integer))> _
<DataMemberAttribute> _
Public Property BackColorAsARGB As ARGBColor
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As ARGBColor

value = instance.BackColorAsARGB

instance.BackColorAsARGB = value
```

``` csharp
[ColumnAttribute("BACKCOLOR", ManagedType = typeof(int))]
[DataMemberAttribute]
public ARGBColor BackColorAsARGB { get; set; }
```

``` c++
[ColumnAttribute(L"BACKCOLOR", ManagedType = typeof(int))]
[DataMemberAttribute]
public:
property ARGBColor^ BackColorAsARGB {
    ARGBColor^ get ();
    void set (ARGBColor^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ARGBColor](argbcolor-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The button backcolor.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

