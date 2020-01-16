---
title: TaxComponentIndia.TaxComponent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxComponent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxComponentIndia.TaxComponent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcomponentindia.taxcomponent(v=AX.60)
ms:contentKeyID: 62210784
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxComponentIndia.TaxComponent
dev_langs:
- CSharp
- C++
- VB
---

# TaxComponent Property

Gets or sets the component of the tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COMPONENT")> _
<DataMemberAttribute> _
Public Property TaxComponent As String
    Get
    Set
'Usage
Dim instance As TaxComponentIndia
Dim value As String

value = instance.TaxComponent

instance.TaxComponent = value
```

``` csharp
[ColumnAttribute("COMPONENT")]
[DataMemberAttribute]
public string TaxComponent { get; set; }
```

``` c++
[ColumnAttribute(L"COMPONENT")]
[DataMemberAttribute]
public:
property String^ TaxComponent {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxComponentIndia Class](taxcomponentindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

