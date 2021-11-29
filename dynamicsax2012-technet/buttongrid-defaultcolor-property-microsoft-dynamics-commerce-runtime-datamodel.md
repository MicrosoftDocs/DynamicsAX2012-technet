---
title: ButtonGrid.DefaultColor Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DefaultColor Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.DefaultColor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongrid.defaultcolor(v=AX.60)
ms:contentKeyID: 62206892
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.DefaultColor
dev_langs:
- CSharp
- C++
- VB
---

# DefaultColor Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the default color for buttons in this button grid.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DEFAULTCOLOR")> _
Public Property DefaultColor As Integer
    Get
    Set
'Usage
Dim instance As ButtonGrid
Dim value As Integer

value = instance.DefaultColor

instance.DefaultColor = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DEFAULTCOLOR")]
public int DefaultColor { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DEFAULTCOLOR")]
public:
property int DefaultColor {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The default color.  

## See Also

#### Reference

[ButtonGrid Class](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

