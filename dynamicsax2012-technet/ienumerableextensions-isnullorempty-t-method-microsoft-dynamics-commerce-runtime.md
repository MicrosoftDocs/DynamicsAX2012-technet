---
title: IEnumerableExtensions.IsNullOrEmpty(T) Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsNullOrEmpty(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.IEnumerableExtensions.IsNullOrEmpty``1(System.Collections.Generic.IEnumerable{``0})
ms:mtpsurl: https://technet.microsoft.com/library/Dn696621(v=AX.60)
ms:contentKeyID: 62208020
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.IEnumerableExtensions.IsNullOrEmpty``1
dev_langs:
- CSharp
- C++
- VB
---

# IsNullOrEmpty(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the current collection is null or empty.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function IsNullOrEmpty(Of T) ( _
    collection As IEnumerable(Of T) _
) As Boolean
'Usage
Dim collection As IEnumerable(Of T)
Dim returnValue As Boolean

returnValue = collection.IsNullOrEmpty()
```

``` csharp
public static bool IsNullOrEmpty<T>(
    this IEnumerable<T> collection
)
```

``` c++
[ExtensionAttribute]
public:
generic<typename T>
static bool IsNullOrEmpty(
    IEnumerable<T>^ collection
)
```

#### Type Parameters

  - T

#### Parameters

  - collection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<T\>  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the collection is null or empty.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<T\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[IEnumerableExtensions Class](ienumerableextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

