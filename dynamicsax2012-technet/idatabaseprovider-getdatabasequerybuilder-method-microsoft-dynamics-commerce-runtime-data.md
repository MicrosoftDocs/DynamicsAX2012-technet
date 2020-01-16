---
title: IDatabaseProvider.GetDatabaseQueryBuilder Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDatabaseQueryBuilder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.GetDatabaseQueryBuilder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseprovider.getdatabasequerybuilder(v=AX.60)
ms:contentKeyID: 65320500
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.GetDatabaseQueryBuilder
dev_langs:
- CSharp
- C++
- VB
---

# GetDatabaseQueryBuilder Method

Gets a specific implementation of [IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetDatabaseQueryBuilder As IDatabaseQueryBuilder
'Usage
Dim instance As IDatabaseProvider
Dim returnValue As IDatabaseQueryBuilder

returnValue = instance.GetDatabaseQueryBuilder()
```

``` csharp
IDatabaseQueryBuilder GetDatabaseQueryBuilder()
```

``` c++
IDatabaseQueryBuilder^ GetDatabaseQueryBuilder()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md)  
Returns a specific implementation of [IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[IDatabaseProvider Interface](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

