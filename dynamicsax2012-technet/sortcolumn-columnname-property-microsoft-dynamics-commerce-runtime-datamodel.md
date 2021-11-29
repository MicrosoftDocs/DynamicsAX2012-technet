---
title: SortColumn.ColumnName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ColumnName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn.ColumnName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.sortcolumn.columnname(v=AX.60)
ms:contentKeyID: 65320455
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn.ColumnName
dev_langs:
- CSharp
- C++
- VB
---

# ColumnName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the name of the column.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ColumnName As String
    Get
    Set
'Usage
Dim instance As SortColumn
Dim value As String

value = instance.ColumnName

instance.ColumnName = value
```

``` csharp
[DataMemberAttribute]
public string ColumnName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ColumnName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name of the column.  

## See Also

#### Reference

[SortColumn Class](sortcolumn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

