---
title: OfflineSyncStatsLine.ScopeName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ScopeName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine.ScopeName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.offlinesyncstatsline.scopename(v=AX.60)
ms:contentKeyID: 65322180
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine.ScopeName
dev_langs:
- CSharp
- C++
- VB
---

# ScopeName Property

Gets or sets the scope name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SCOPENAME")> _
<DataMemberAttribute> _
Public Property ScopeName As String
    Get
    Set
'Usage
Dim instance As OfflineSyncStatsLine
Dim value As String

value = instance.ScopeName

instance.ScopeName = value
```

``` csharp
[ColumnAttribute("SCOPENAME")]
[DataMemberAttribute]
public string ScopeName { get; set; }
```

``` c++
[ColumnAttribute(L"SCOPENAME")]
[DataMemberAttribute]
public:
property String^ ScopeName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OfflineSyncStatsLine Class](offlinesyncstatsline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

