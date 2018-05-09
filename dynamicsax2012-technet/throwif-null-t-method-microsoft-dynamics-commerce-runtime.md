---
title: ThrowIf.Null(T) Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Null(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ThrowIf.Null``1(``0,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn990871(v=AX.60)
ms:contentKeyID: 65322062
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ThrowIf.Null``1
dev_langs:
- CSharp
- C++
- VB
---

# Null(T) Method

Throws ArgumentNullException if the argument is null, otherwise passes it through.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub Null(Of T As Class) ( _
    arg As T, _
    parameterName As String _
)
'Usage
Dim arg As T
Dim parameterName As String

ThrowIf.Null(arg, parameterName)
```

``` csharp
public static void Null<T>(
    T arg,
    string parameterName
)
where T : class
```

``` c++
public:
generic<typename T>
where T : ref class
static void Null(
    T arg, 
    String^ parameterName
)
```

#### Type Parameters

  - T

#### Parameters

  - arg  
    Type: T  

<!-- end list -->

  - parameterName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ThrowIf Class](throwif-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

