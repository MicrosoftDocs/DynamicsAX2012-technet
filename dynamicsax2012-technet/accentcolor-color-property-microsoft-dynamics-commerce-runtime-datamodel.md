---
title: AccentColor.Color Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Color Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AccentColor.Color
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.accentcolor.color(v=AX.60)
ms:contentKeyID: 62212898
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AccentColor.Color
dev_langs:
- CSharp
- C++
- VB
---

# Color Property

Gets or sets the value of color.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COLOR")> _
Public Property Color As Integer
    Get
    Set
'Usage
Dim instance As AccentColor
Dim value As Integer

value = instance.Color

instance.Color = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COLOR")]
public int Color { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COLOR")]
public:
property int Color {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[AccentColor Class](accentcolor-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

