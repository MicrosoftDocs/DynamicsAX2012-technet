---
title: DataRowCollection Class (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: DataRowCollection Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRowCollection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datarowcollection(v=AX.60)
ms:contentKeyID: 65318846
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRowCollection
dev_langs:
- CSharp
- C++
- VB
---

# DataRowCollection Class

Represents a collection of rows contained in a data table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class DataRowCollection _
    Inherits DbElementCollection(Of DataRow)
'Usage
Dim instance As DataRowCollection
```

``` csharp
public sealed class DataRowCollection : DbElementCollection<DataRow>
```

``` c++
public ref class DataRowCollection sealed : public DbElementCollection<DataRow^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)\<[DataRow](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRowCollection  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

