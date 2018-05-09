---
title: TillLayout.LayoutId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LayoutId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.LayoutId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.layoutid(v=AX.60)
ms:contentKeyID: 62209134
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.LayoutId
dev_langs:
- CSharp
- C++
- VB
---

# LayoutId Property

Gets or sets the layout identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LAYOUTID")> _
Public Property LayoutId As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.LayoutId

instance.LayoutId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LAYOUTID")]
public string LayoutId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LAYOUTID")]
public:
property String^ LayoutId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The layout identifier.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

