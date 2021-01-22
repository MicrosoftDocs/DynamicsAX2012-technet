---
title: ButtonGrid.Name Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Name Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.Name
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongrid.name(v=AX.60)
ms:contentKeyID: 62211249
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid.Name
dev_langs:
- CSharp
- C++
- VB
---

# Name Property

Gets or sets the button grid name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NAME")> _
<DataMemberAttribute> _
Public Property Name As String
    Get
    Set
'Usage
Dim instance As ButtonGrid
Dim value As String

value = instance.Name

instance.Name = value
```

``` csharp
[ColumnAttribute("NAME")]
[DataMemberAttribute]
public string Name { get; set; }
```

``` c++
[ColumnAttribute(L"NAME")]
[DataMemberAttribute]
public:
property String^ Name {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The button grid name.  

## See Also

#### Reference

[ButtonGrid Class](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

