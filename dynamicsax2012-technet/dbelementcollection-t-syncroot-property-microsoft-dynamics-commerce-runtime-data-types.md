---
title: DbElementCollection(T).SyncRoot Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: SyncRoot Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.SyncRoot
ms:mtpsurl: https://technet.microsoft.com/library/Dn991299(v=AX.60)
ms:contentKeyID: 65323238
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.SyncRoot
dev_langs:
- CSharp
- C++
- VB
---

# SyncRoot Property

Gets an object that can be used to synchronize access to the collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SyncRoot As Object
    Get
'Usage
Dim instance As DbElementCollection
Dim value As Object

value = instance.SyncRoot
```

``` csharp
public Object SyncRoot { get; }
```

``` c++
public:
virtual property Object^ SyncRoot {
    Object^ get () sealed;
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)).  

#### Implements

[ICollection.SyncRoot](https://technet.microsoft.com/library/ccad5w5z\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

