---
title: CommerceRuntimeException.ErrorResourceId Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ErrorResourceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException.ErrorResourceId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeexception.errorresourceid(v=AX.60)
ms:contentKeyID: 49851130
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException.ErrorResourceId
dev_langs:
- CSharp
- C++
- VB
---

# ErrorResourceId Property

Gets or sets the error resource identifier associated with this exception.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ErrorResourceId As String
    Get
    Protected Set
'Usage
Dim instance As CommerceRuntimeException
Dim value As String

value = instance.ErrorResourceId

instance.ErrorResourceId = value
```

``` csharp
public string ErrorResourceId { get; protected set; }
```

``` c++
public:
property String^ ErrorResourceId {
    String^ get ();
    protected: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The error code.  

## See Also

#### Reference

[CommerceRuntimeException Class](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

