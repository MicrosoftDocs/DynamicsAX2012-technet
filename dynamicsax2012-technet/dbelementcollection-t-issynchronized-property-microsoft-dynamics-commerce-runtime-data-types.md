---
title: DbElementCollection(T).IsSynchronized Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: IsSynchronized Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.IsSynchronized
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn988343(v=AX.60)
ms:contentKeyID: 65317896
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.IsSynchronized
dev_langs:
- CSharp
- C++
- VB
---

# IsSynchronized Property

Gets a value indicating whether access to the collection is synchronized (thread safe).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property IsSynchronized As Boolean
    Get
'Usage
Dim instance As DbElementCollection
Dim value As Boolean

value = instance.IsSynchronized
```

``` csharp
public bool IsSynchronized { get; }
```

``` c++
public:
virtual property bool IsSynchronized {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

#### Implements

[ICollection.IsSynchronized](https://technet.microsoft.com/en-us/library/d74ky11w\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

