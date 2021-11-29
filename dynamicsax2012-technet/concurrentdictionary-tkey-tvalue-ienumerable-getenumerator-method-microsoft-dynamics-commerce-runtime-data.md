---
title: ConcurrentDictionary(TKey, TValue).IEnumerable.GetEnumerator Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IEnumerable.GetEnumerator Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.System#Collections#IEnumerable#GetEnumerator
ms:mtpsurl: https://technet.microsoft.com/library/Dn988159(v=AX.60)
ms:contentKeyID: 65317206
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- IEnumerable.GetEnumerator
- ConcurrentDictionary`2.IEnumerable.GetEnumerator
- Microsoft.Dynamics.Commerce.Runtime.Data.ConcurrentDictionary`2.IEnumerable.GetEnumerator
dev_langs:
- CSharp
- C++
- VB
---

# IEnumerable.GetEnumerator Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Implements the GetEnumerator of IEnumerable explicitly.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Private Function GetEnumerator As IEnumerator
    Implements IEnumerable.GetEnumerator
'Usage
Dim instance As ConcurrentDictionary
Dim returnValue As IEnumerator

returnValue = CType(instance, IEnumerable).GetEnumerator()
```

``` csharp
IEnumerator IEnumerable.GetEnumerator()
```

``` c++
private:
virtual IEnumerator^ GetEnumerator() sealed = IEnumerable::GetEnumerator
```

#### Return Value

Type: [System.Collections.IEnumerator](https://technet.microsoft.com/library/1t2267t6\(v=ax.60\))  
Returns the enumerator.  

#### Implements

[IEnumerable.GetEnumerator()](https://technet.microsoft.com/library/5zae5365\(v=ax.60\))  

## See Also

#### Reference

[ConcurrentDictionary\<TKey, TValue\> Class](concurrentdictionary-tkey-tvalue-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

