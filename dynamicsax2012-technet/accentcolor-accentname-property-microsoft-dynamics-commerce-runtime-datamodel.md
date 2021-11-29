---
title: AccentColor.AccentName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccentName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AccentColor.AccentName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.accentcolor.accentname(v=AX.60)
ms:contentKeyID: 62212984
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AccentColor.AccentName
dev_langs:
- CSharp
- C++
- VB
---

# AccentName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of accent name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ACCENTNAME")> _
Public Property AccentName As String
    Get
    Set
'Usage
Dim instance As AccentColor
Dim value As String

value = instance.AccentName

instance.AccentName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ACCENTNAME")]
public string AccentName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ACCENTNAME")]
public:
property String^ AccentName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[AccentColor Class](accentcolor-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

