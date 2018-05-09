---
title: DataSet.Tables Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Tables Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet.Tables
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.types.dataset.tables(v=AX.60)
ms:contentKeyID: 65320864
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet.Tables
dev_langs:
- CSharp
- C++
- VB
---

# Tables Property

Gets the collection of tables.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Tables As IList(Of DataTable)
    Get
    Private Set
'Usage
Dim instance As DataSet
Dim value As IList(Of DataTable)

value = instance.Tables
```

``` csharp
public IList<DataTable> Tables { get; private set; }
```

``` c++
public:
property IList<DataTable^>^ Tables {
    IList<DataTable^>^ get ();
    private: void set (IList<DataTable^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[DataSet Class](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

