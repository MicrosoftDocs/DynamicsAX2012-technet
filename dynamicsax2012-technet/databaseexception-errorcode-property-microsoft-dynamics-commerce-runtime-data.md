---
title: DatabaseException.ErrorCode Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ErrorCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseException.ErrorCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databaseexception.errorcode(v=AX.60)
ms:contentKeyID: 65322793
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseException.ErrorCode
dev_langs:
- CSharp
- C++
- VB
---

# ErrorCode Property

Gets the database error code for this exception.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ErrorCode As DatabaseErrorCode
    Get
    Private Set
'Usage
Dim instance As DatabaseException
Dim value As DatabaseErrorCode

value = instance.ErrorCode
```

``` csharp
public DatabaseErrorCode ErrorCode { get; private set; }
```

``` c++
public:
property DatabaseErrorCode ErrorCode {
    DatabaseErrorCode get ();
    private: void set (DatabaseErrorCode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode](databaseerrorcode-enumeration-microsoft-dynamics-commerce-runtime-data.md)  
Returns [DatabaseErrorCode](databaseerrorcode-enumeration-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[DatabaseException Class](databaseexception-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

