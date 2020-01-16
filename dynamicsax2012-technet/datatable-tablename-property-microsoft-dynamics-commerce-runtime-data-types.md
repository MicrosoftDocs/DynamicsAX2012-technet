---
title: DataTable.TableName Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: TableName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.TableName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datatable.tablename(v=AX.60)
ms:contentKeyID: 65323242
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.TableName
dev_langs:
- CSharp
- C++
- VB
---

# TableName Property

Gets or sets this table name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property TableName As String
    Get
    Set
'Usage
Dim instance As DataTable
Dim value As String

value = instance.TableName

instance.TableName = value
```

``` csharp
public string TableName { get; set; }
```

``` c++
public:
property String^ TableName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DataTable Class](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

