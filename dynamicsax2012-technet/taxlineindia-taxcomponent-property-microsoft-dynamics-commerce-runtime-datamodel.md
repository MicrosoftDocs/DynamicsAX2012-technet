---
title: TaxLineIndia.TaxComponent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxComponent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxComponent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.taxcomponent(v=AX.60)
ms:contentKeyID: 62214428
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxComponent
dev_langs:
- CSharp
- C++
- VB
---

# TaxComponent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax component.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXCOMPONENT")> _
<DataMemberAttribute> _
Public Property TaxComponent As String
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As String

value = instance.TaxComponent

instance.TaxComponent = value
```

``` csharp
[ColumnAttribute("TAXCOMPONENT")]
[DataMemberAttribute]
public string TaxComponent { get; set; }
```

``` c++
[ColumnAttribute(L"TAXCOMPONENT")]
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

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

