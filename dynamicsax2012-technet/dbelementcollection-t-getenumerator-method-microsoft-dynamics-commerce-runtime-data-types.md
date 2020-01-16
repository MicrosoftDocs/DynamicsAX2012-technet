---
title: DbElementCollection(T).GetEnumerator Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: GetEnumerator Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.GetEnumerator
ms:mtpsurl: https://technet.microsoft.com/library/Dn988429(v=AX.60)
ms:contentKeyID: 65317983
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.GetEnumerator
dev_langs:
- CSharp
- C++
- VB
---

# GetEnumerator Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetEnumerator As IEnumerator
'Usage
Dim instance As DbElementCollection
Dim returnValue As IEnumerator

returnValue = instance.GetEnumerator()
```

``` csharp
public IEnumerator GetEnumerator()
```

``` c++
public:
virtual IEnumerator^ GetEnumerator() sealed
```

#### Return Value

Type: [System.Collections.IEnumerator](https://technet.microsoft.com/library/1t2267t6\(v=ax.60\))  
Returns [IEnumerator](https://technet.microsoft.com/library/1t2267t6\(v=ax.60\)).  

#### Implements

[IEnumerable.GetEnumerator()](https://technet.microsoft.com/library/5zae5365\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

