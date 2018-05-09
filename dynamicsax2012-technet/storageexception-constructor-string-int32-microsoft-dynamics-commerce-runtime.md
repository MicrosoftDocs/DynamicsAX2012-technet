---
title: StorageException Constructor (String, Int32) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: StorageException Constructor (String, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.StorageException.#ctor(System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.storageexception.storageexception(v=AX.60)
ms:contentKeyID: 49851694
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# StorageException Constructor (String, Int32)

Initializes a new instance of the [StorageException](storageexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    errorCode As Integer _
)
'Usage
Dim errorResourceId As String
Dim errorCode As Integer

Dim instance As New StorageException(errorResourceId, _
    errorCode)
```

``` csharp
public StorageException(
    string errorResourceId,
    int errorCode
)
```

``` c++
public:
StorageException(
    String^ errorResourceId, 
    int errorCode
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - errorCode  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[StorageException Class](storageexception-class-microsoft-dynamics-commerce-runtime.md)

[StorageException Overload](storageexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

