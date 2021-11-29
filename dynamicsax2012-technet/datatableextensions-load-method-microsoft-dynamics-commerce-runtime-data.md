---
title: DataTableExtensions.Load Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Load Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataTableExtensions.Load(Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection,Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datatableextensions.load(v=AX.60)
ms:contentKeyID: 65321337
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataTableExtensions.Load
dev_langs:
- CSharp
- C++
- VB
---

# Load Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Loads records from the database into a data table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub Load ( _
    table As DataTable, _
    connection As IDatabaseConnection, _
    provider As IDatabaseProvider _
)
'Usage
Dim table As DataTable
Dim connection As IDatabaseConnection
Dim provider As IDatabaseProvider

table.Load(connection, provider)
```

``` csharp
public static void Load(
    this DataTable table,
    IDatabaseConnection connection,
    IDatabaseProvider provider
)
```

``` c++
[ExtensionAttribute]
public:
static void Load(
    DataTable^ table, 
    IDatabaseConnection^ connection, 
    IDatabaseProvider^ provider
)
```

#### Parameters

  - table  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - connection  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - provider  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DataTableExtensions Class](datatableextensions-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

