---
title: StorageException Constructor (String) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: StorageException Constructor (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.StorageException.#ctor(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.storageexception.storageexception(v=AX.60)
ms:contentKeyID: 49836763
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# StorageException Constructor (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [StorageException](storageexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String _
)
'Usage
Dim errorResourceId As String

Dim instance As New StorageException(errorResourceId)
```

``` csharp
public StorageException(
    string errorResourceId
)
```

``` c++
public:
StorageException(
    String^ errorResourceId
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[StorageException Class](storageexception-class-microsoft-dynamics-commerce-runtime.md)

[StorageException Overload](storageexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

