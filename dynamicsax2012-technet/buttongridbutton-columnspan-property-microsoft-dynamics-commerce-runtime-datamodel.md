---
title: ButtonGridButton.ColumnSpan Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ColumnSpan Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.ColumnSpan
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.columnspan(v=AX.60)
ms:contentKeyID: 62212635
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.ColumnSpan
dev_langs:
- CSharp
- C++
- VB
---

# ColumnSpan Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the button column span.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COLSPAN")> _
<DataMemberAttribute> _
Public Property ColumnSpan As Integer
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As Integer

value = instance.ColumnSpan

instance.ColumnSpan = value
```

``` csharp
[ColumnAttribute("COLSPAN")]
[DataMemberAttribute]
public int ColumnSpan { get; set; }
```

``` c++
[ColumnAttribute(L"COLSPAN")]
[DataMemberAttribute]
public:
property int ColumnSpan {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The button column span.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

