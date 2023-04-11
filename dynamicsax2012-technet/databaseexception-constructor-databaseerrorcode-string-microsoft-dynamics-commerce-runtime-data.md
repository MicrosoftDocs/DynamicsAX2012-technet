---
title: DatabaseException Constructor (DatabaseErrorCode, String) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseException Constructor (DatabaseErrorCode, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseException.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databaseexception.databaseexception(v=AX.60)
ms:contentKeyID: 65321760
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DatabaseException Constructor (DatabaseErrorCode, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [DatabaseException](databaseexception-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorCode As DatabaseErrorCode, _
    message As String _
)
'Usage
Dim errorCode As DatabaseErrorCode
Dim message As String

Dim instance As New DatabaseException(errorCode, _
    message)
```

``` csharp
public DatabaseException(
    DatabaseErrorCode errorCode,
    string message
)
```

``` c++
public:
DatabaseException(
    DatabaseErrorCode errorCode, 
    String^ message
)
```

#### Parameters

  - errorCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode](databaseerrorcode-enumeration-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DatabaseException Class](databaseexception-class-microsoft-dynamics-commerce-runtime-data.md)

[DatabaseException Overload](databaseexception-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

