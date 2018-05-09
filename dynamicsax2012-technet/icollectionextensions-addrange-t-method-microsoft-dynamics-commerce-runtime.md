---
title: ICollectionExtensions.AddRange(T) Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: AddRange(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICollectionExtensions.AddRange``1(System.Collections.Generic.ICollection{``0},System.Collections.Generic.IEnumerable{``0})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ760927(v=AX.60)
ms:contentKeyID: 49833482
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICollectionExtensions.AddRange``1
dev_langs:
- CSharp
- C++
- VB
---

# AddRange(T) Method

Adds the elements of the specified collection to the end of the [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AddRange(Of T) ( _
    thisCollection As ICollection(Of T), _
    collection As IEnumerable(Of T) _
)
'Usage
Dim thisCollection As ICollection(Of T)
Dim collection As IEnumerable(Of T)

thisCollection.AddRange(collection)
```

``` csharp
public static void AddRange<T>(
    this ICollection<T> thisCollection,
    IEnumerable<T> collection
)
```

``` c++
[ExtensionAttribute]
public:
generic<typename T>
static void AddRange(
    ICollection<T>^ thisCollection, 
    IEnumerable<T>^ collection
)
```

#### Type Parameters

  - T

#### Parameters

  - thisCollection  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<T\>  

<!-- end list -->

  - collection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<T\>  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<T\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ICollectionExtensions Class](icollectionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

