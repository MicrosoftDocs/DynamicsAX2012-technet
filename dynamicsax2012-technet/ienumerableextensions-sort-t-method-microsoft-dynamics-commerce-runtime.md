---
title: IEnumerableExtensions.Sort(T) Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Sort(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.IEnumerableExtensions.Sort``1(System.Collections.Generic.IEnumerable{``0},System.Collections.Generic.List{Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn}.Enumerator)
ms:mtpsurl: https://technet.microsoft.com/library/Dn968139(v=AX.60)
ms:contentKeyID: 65320503
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.IEnumerableExtensions.Sort``1
dev_langs:
- CSharp
- C++
- VB
---

# Sort(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Sort(Of T As CommerceEntity) ( _
    collection As IEnumerable(Of T), _
    enumerator As List<T>.Enumerator _
) As IEnumerable(Of T)
'Usage
Dim collection As IEnumerable(Of T)
Dim enumerator As List<T>.Enumerator
Dim returnValue As IEnumerable(Of T)

returnValue = collection.Sort(enumerator)
```

``` csharp
public static IEnumerable<T> Sort<T>(
    this IEnumerable<T> collection,
    List<T>.Enumerator enumerator
)
where T : CommerceEntity
```

``` c++
[ExtensionAttribute]
public:
generic<typename T>
where T : CommerceEntity
static IEnumerable<T>^ Sort(
    IEnumerable<T>^ collection, 
    List<T>.Enumerator enumerator
)
```

#### Type Parameters

  - T

#### Parameters

  - collection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<T\>  

<!-- end list -->

  - enumerator  
    Type: [System.Collections.Generic.List\<T\>.Enumerator](https://technet.microsoft.com/library/x854yt9s\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<T\>  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<T\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[IEnumerableExtensions Class](ienumerableextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

