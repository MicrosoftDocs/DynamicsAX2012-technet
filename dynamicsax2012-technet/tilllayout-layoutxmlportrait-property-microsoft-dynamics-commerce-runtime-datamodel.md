---
title: TillLayout.LayoutXmlPortrait Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LayoutXmlPortrait Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.LayoutXmlPortrait
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.layoutxmlportrait(v=AX.60)
ms:contentKeyID: 65320388
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.LayoutXmlPortrait
dev_langs:
- CSharp
- C++
- VB
---

# LayoutXmlPortrait Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LAYOUTXMLPORTRAIT")> _
<DataMemberAttribute> _
Public Property LayoutXmlPortrait As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.LayoutXmlPortrait

instance.LayoutXmlPortrait = value
```

``` csharp
[ColumnAttribute("LAYOUTXMLPORTRAIT")]
[DataMemberAttribute]
public string LayoutXmlPortrait { get; set; }
```

``` c++
[ColumnAttribute(L"LAYOUTXMLPORTRAIT")]
[DataMemberAttribute]
public:
property String^ LayoutXmlPortrait {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

