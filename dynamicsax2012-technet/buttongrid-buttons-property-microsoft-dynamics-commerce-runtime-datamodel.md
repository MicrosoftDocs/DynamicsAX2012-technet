---
title: ButtonGrid.Buttons Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Buttons Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.Buttons
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongrid.buttons(v=AX.60)
ms:contentKeyID: 62211365
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.Buttons
dev_langs:
- CSharp
- C++
- VB
---

# Buttons Property

Gets or sets the collection of button grid buttons.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Buttons As IEnumerable(Of ButtonGridButton)
    Get
    Set
'Usage
Dim instance As ButtonGrid
Dim value As IEnumerable(Of ButtonGridButton)

value = instance.Buttons

instance.Buttons = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ButtonGridButton> Buttons { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ButtonGridButton^>^ Buttons {
    IEnumerable<ButtonGridButton^>^ get ();
    void set (IEnumerable<ButtonGridButton^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ButtonGridButton](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ButtonGrid Class](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

