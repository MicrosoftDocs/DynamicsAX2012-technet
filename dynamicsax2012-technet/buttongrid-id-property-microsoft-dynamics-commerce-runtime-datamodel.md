---
title: ButtonGrid.Id Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.Id
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongrid.id(v=AX.60)
ms:contentKeyID: 62208149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.Id
dev_langs:
- CSharp
- C++
- VB
---

# Id Property

Gets or sets the button grid identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BUTTONGRIDID")> _
Public Property Id As String
    Get
    Set
'Usage
Dim instance As ButtonGrid
Dim value As String

value = instance.Id

instance.Id = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BUTTONGRIDID")]
public string Id { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BUTTONGRIDID")]
public:
property String^ Id {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The button grid identifier.  

## See Also

#### Reference

[ButtonGrid Class](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

