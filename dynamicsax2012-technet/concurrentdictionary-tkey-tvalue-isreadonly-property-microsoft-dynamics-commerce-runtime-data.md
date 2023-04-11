---
title: ConcurrentDictionary(TKey, TValue).IsReadOnly Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsReadOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.IsReadOnly
ms:mtpsurl: https://technet.microsoft.com/library/Dn990470(v=AX.60)
ms:contentKeyID: 65321410
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.IsReadOnly
dev_langs:
- CSharp
- C++
- VB
---

# IsReadOnly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the dictionary is read only collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property IsReadOnly As Boolean
    Get
'Usage
Dim instance As ConcurrentDictionary
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

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

