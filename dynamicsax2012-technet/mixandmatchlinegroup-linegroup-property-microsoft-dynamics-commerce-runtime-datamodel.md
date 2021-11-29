---
title: MixAndMatchLineGroup.LineGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.MixAndMatchLineGroup.LineGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.mixandmatchlinegroup.linegroup(v=AX.60)
ms:contentKeyID: 49853104
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.MixAndMatchLineGroup.LineGroup
dev_langs:
- CSharp
- C++
- VB
---

# LineGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the line group name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEGROUP")> _
Public Property LineGroup As String
    Get
    Friend Set
'Usage
Dim instance As MixAndMatchLineGroup
Dim value As String

value = instance.LineGroup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEGROUP")]
public string LineGroup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEGROUP")]
public:
property String^ LineGroup {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[MixAndMatchLineGroup Class](mixandmatchlinegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

