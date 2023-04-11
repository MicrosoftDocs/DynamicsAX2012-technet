---
title: DbElementCollection(T).GetKey Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.GetKey(`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn969346(v=AX.60)
ms:contentKeyID: 65322959
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the key used to represent an element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetKey ( _
    value As T _
) As String
'Usage
Dim value As T
Dim returnValue As String

returnValue = Me.GetKey(value)
```

``` csharp
protected virtual string GetKey(
    T value
)
```

``` c++
protected:
virtual String^ GetKey(
    T value
)
```

#### Parameters

  - value  
    Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The element's key.  

## Remarks

Returning null means that named keys are not used for indexing an element.

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

