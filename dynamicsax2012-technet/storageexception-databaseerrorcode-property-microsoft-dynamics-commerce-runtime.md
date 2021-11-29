---
title: StorageException.DatabaseErrorCode Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DatabaseErrorCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.StorageException.DatabaseErrorCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.storageexception.databaseerrorcode(v=AX.60)
ms:contentKeyID: 49848690
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.StorageException.DatabaseErrorCode
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseErrorCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the database error code corresponding to the operation that failed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property DatabaseErrorCode As Integer
    Get
    Private Set
'Usage
Dim instance As StorageException
Dim value As Integer

value = instance.DatabaseErrorCode
```

``` csharp
public int DatabaseErrorCode { get; private set; }
```

``` c++
public:
property int DatabaseErrorCode {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[StorageException Class](storageexception-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

