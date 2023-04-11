---
title: DbElementCollection(T).Count Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Count Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Count
ms:mtpsurl: https://technet.microsoft.com/library/Dn968414(v=AX.60)
ms:contentKeyID: 65321030
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Count
dev_langs:
- CSharp
- C++
- VB
---

# Count Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number of elements in this collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Count As Integer
    Get
'Usage
Dim instance As DbElementCollection
Dim value As Integer

value = instance.Count
```

``` csharp
public int Count { get; }
```

``` c++
public:
virtual property int Count {
    int get () sealed;
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

#### Implements

[ICollection.Count](https://technet.microsoft.com/library/2yz8a4x3\(v=ax.60\))  
[ICollection\<T\>.Count](https://technet.microsoft.com/library/5s3kzhec\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

