---
title: DatabaseException Constructor (String, Exception) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseException Constructor (String, Exception)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseException.#ctor(System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.databaseexception.databaseexception(v=AX.60)
ms:contentKeyID: 65320807
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DatabaseException Constructor (String, Exception)

Initializes a new instance of the [DatabaseException](databaseexception-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    message As String, _
    innerException As Exception _
)
'Usage
Dim message As String
Dim innerException As Exception

Dim instance As New DatabaseException(message, _
    innerException)
```

``` csharp
public DatabaseException(
    string message,
    Exception innerException
)
```

``` c++
public:
DatabaseException(
    String^ message, 
    Exception^ innerException
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - innerException  
    Type: [System.Exception](https://technet.microsoft.com/en-us/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[DatabaseException Class](databaseexception-class-microsoft-dynamics-commerce-runtime-data.md)

[DatabaseException Overload](databaseexception-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

