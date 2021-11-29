---
title: ConcurrentDictionary(TKey, TValue).Count Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Count Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Count
ms:mtpsurl: https://technet.microsoft.com/library/Dn968246(v=AX.60)
ms:contentKeyID: 65320609
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.Count
dev_langs:
- CSharp
- C++
- VB
---

# Count Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number of elements contained in the Dictionary.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Count As Integer
    Get
'Usage
Dim instance As ConcurrentDictionary
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

[ICollection\<T\>.Count](https://technet.microsoft.com/library/5s3kzhec\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

