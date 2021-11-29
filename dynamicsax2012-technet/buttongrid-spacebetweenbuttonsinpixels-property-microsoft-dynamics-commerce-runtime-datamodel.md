---
title: ButtonGrid.SpaceBetweenButtonsInPixels Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SpaceBetweenButtonsInPixels Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.SpaceBetweenButtonsInPixels
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongrid.spacebetweenbuttonsinpixels(v=AX.60)
ms:contentKeyID: 62212926
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.SpaceBetweenButtonsInPixels
dev_langs:
- CSharp
- C++
- VB
---

# SpaceBetweenButtonsInPixels Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the between buttons (in pixels) in this button grid.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SPACEBETWEENBUTTONS")> _
Public Property SpaceBetweenButtonsInPixels As Integer
    Get
    Set
'Usage
Dim instance As ButtonGrid
Dim value As Integer

value = instance.SpaceBetweenButtonsInPixels

instance.SpaceBetweenButtonsInPixels = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SPACEBETWEENBUTTONS")]
public int SpaceBetweenButtonsInPixels { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SPACEBETWEENBUTTONS")]
public:
property int SpaceBetweenButtonsInPixels {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Pixel space between buttons.  

## See Also

#### Reference

[ButtonGrid Class](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

