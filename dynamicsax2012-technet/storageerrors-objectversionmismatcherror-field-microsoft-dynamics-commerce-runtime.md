---
title: StorageErrors.ObjectVersionMismatchError Field (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ObjectVersionMismatchError Field
ms:assetid: F:Microsoft.Dynamics.Commerce.Runtime.StorageErrors.ObjectVersionMismatchError
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.storageerrors.objectversionmismatcherror(v=AX.60)
ms:contentKeyID: 49830246
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.StorageErrors.ObjectVersionMismatchError
dev_langs:
- CSharp
- C++
- VB
---

# ObjectVersionMismatchError Field


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates that the version of the object in the database is different from the one that is attempted to be saved indicating an optmistic concurrency issue.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Const ObjectVersionMismatchError As String
'Usage
Dim value As String

value = StorageErrors.ObjectVersionMismatchError
```

``` csharp
public const string ObjectVersionMismatchError
```

``` c++
public:
literal String^ ObjectVersionMismatchError
```

## See Also

#### Reference

[StorageErrors Class](storageerrors-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

