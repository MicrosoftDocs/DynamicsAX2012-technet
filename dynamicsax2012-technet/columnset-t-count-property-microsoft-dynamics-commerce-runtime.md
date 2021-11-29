---
title: ColumnSet(T).Count Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Count Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.Count
ms:mtpsurl: https://technet.microsoft.com/library/Dn684364(v=AX.60)
ms:contentKeyID: 62203504
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.Count
dev_langs:
- CSharp
- C++
- VB
---

# Count Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number of columns that have been explicitly added to the set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Count As Integer
    Get
'Usage
Dim instance As ColumnSet
Dim value As Integer

value = instance.Count
```

``` csharp
public int Count { get; }
```

``` c++
public:
property int Count {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ColumnSet\<T\> Class](columnset-t-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

