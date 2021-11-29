---
title: DatabaseContext.DatabaseProvider Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseProvider Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.DatabaseProvider
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasecontext.databaseprovider(v=AX.60)
ms:contentKeyID: 65321293
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.DatabaseProvider
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseProvider Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the database provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Protected ReadOnly Property DatabaseProvider As IDatabaseProvider
    Get
'Usage
Dim value As IDatabaseProvider

value = Me.DatabaseProvider
```

``` csharp
protected IDatabaseProvider DatabaseProvider { get; }
```

``` c++
protected:
property IDatabaseProvider^ DatabaseProvider {
    IDatabaseProvider^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)  
Returns [IDatabaseProvider](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

