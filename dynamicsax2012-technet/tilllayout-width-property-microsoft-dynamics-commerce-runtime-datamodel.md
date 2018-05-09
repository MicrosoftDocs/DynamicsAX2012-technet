---
title: TillLayout.Width Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Width Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.Width
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.width(v=AX.60)
ms:contentKeyID: 62212041
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.Width
dev_langs:
- CSharp
- C++
- VB
---

# Width Property

Gets or sets the value of screen width.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("WIDTH")> _
Public Property Width As Integer
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As Integer

value = instance.Width

instance.Width = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("WIDTH")]
public int Width { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"WIDTH")]
public:
property int Width {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The screen width.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

