---
title: CommerceRuntimeException Constructor (String) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CommerceRuntimeException Constructor (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException.#ctor(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeexception.commerceruntimeexception(v=AX.60)
ms:contentKeyID: 49852355
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommerceRuntimeException Constructor (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [CommerceRuntimeException](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    errorResourceId As String _
)
'Usage
Dim errorResourceId As String

Dim instance As New CommerceRuntimeException(errorResourceId)
```

``` csharp
protected CommerceRuntimeException(
    string errorResourceId
)
```

``` c++
protected:
CommerceRuntimeException(
    String^ errorResourceId
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CommerceRuntimeException Class](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)

[CommerceRuntimeException Overload](commerceruntimeexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

