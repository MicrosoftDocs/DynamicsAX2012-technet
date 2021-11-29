---
title: DbElementCollection(T).GetKeyByIndex Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: GetKeyByIndex Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.GetKeyByIndex(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/Dn966865(v=AX.60)
ms:contentKeyID: 65317728
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.GetKeyByIndex
dev_langs:
- CSharp
- C++
- VB
---

# GetKeyByIndex Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the key used to represent an element based on its index.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetKeyByIndex ( _
    index As Integer _
) As String
'Usage
Dim index As Integer
Dim returnValue As String

returnValue = Me.GetKeyByIndex(index)
```

``` csharp
protected virtual string GetKeyByIndex(
    int index
)
```

``` c++
protected:
virtual String^ GetKeyByIndex(
    int index
)
```

#### Parameters

  - index  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The element's key.  

## Remarks

Returning null means that named keys are not used for indexing an element.

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

