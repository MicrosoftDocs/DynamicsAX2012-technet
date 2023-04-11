---
title: DbElementCollection(T).GetIndex Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: GetIndex Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.GetIndex(`0,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/Dn989152(v=AX.60)
ms:contentKeyID: 65319107
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.GetIndex
dev_langs:
- CSharp
- C++
- VB
---

# GetIndex Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the index of an element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetIndex ( _
    value As T, _
    key As String _
) As Integer
'Usage
Dim value As T
Dim key As String
Dim returnValue As Integer

returnValue = Me.GetIndex(value, key)
```

``` csharp
protected virtual int GetIndex(
    T value,
    string key
)
```

``` c++
protected:
virtual int GetIndex(
    T value, 
    String^ key
)
```

#### Parameters

  - value  
    Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The index of the element.  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

