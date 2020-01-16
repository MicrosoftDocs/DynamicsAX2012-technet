---
title: TableType.CreateTableSchema Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: CreateTableSchema Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.TableType.CreateTableSchema
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.tabletype.createtableschema(v=AX.60)
ms:contentKeyID: 65319801
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.TableType.CreateTableSchema
dev_langs:
- CSharp
- C++
- VB
---

# CreateTableSchema Method

Creates the table schema.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride Sub CreateTableSchema
'Usage

Me.CreateTableSchema()
```

``` csharp
protected abstract void CreateTableSchema()
```

``` c++
protected:
virtual void CreateTableSchema() abstract
```

## Remarks

The order of the data table columns MUST match the order specified in the TVP.

## See Also

#### Reference

[TableType Class](tabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

