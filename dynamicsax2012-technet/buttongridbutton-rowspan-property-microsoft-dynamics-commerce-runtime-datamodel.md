---
title: ButtonGridButton.RowSpan Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RowSpan Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.RowSpan
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.rowspan(v=AX.60)
ms:contentKeyID: 62214492
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.RowSpan
dev_langs:
- CSharp
- C++
- VB
---

# RowSpan Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the button's row span.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ROWSPAN")> _
Public Property RowSpan As Integer
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As Integer

value = instance.RowSpan

instance.RowSpan = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ROWSPAN")]
public int RowSpan { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ROWSPAN")]
public:
property int RowSpan {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The button's row span.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

