---
title: ConnectionManager.DatabaseProvider Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseProvider Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager.DatabaseProvider
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.connectionmanager.databaseprovider(v=AX.60)
ms:contentKeyID: 65318029
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager.DatabaseProvider
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseProvider Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property DatabaseProvider As IDatabaseProvider
    Get
    Private Set
'Usage
Dim instance As ConnectionManager
Dim value As IDatabaseProvider

value = instance.DatabaseProvider
```

``` csharp
public IDatabaseProvider DatabaseProvider { get; private set; }
```

``` c++
public:
property IDatabaseProvider^ DatabaseProvider {
    IDatabaseProvider^ get ();
    private: void set (IDatabaseProvider^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ConnectionManager Class](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

