---
title: DbElementCollection(T).IsReadOnly Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: IsReadOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.IsReadOnly
ms:mtpsurl: https://technet.microsoft.com/library/Dn989919(v=AX.60)
ms:contentKeyID: 65320375
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.IsReadOnly
dev_langs:
- CSharp
- C++
- VB
---

# IsReadOnly Property

Gets a value indicating whether this collection is read only or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property IsReadOnly As Boolean
    Get
'Usage
Dim instance As DbElementCollection
Dim value As Boolean

value = instance.IsReadOnly
```

``` csharp
public bool IsReadOnly { get; }
```

``` c++
public:
virtual property bool IsReadOnly {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

#### Implements

[ICollection\<T\>.IsReadOnly](https://technet.microsoft.com/library/0cfatk9t\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

