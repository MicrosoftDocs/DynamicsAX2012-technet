---
title: DataCacheAccessor.CalculateCollectionHash(T) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CalculateCollectionHash(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateCollectionHash``1(System.Collections.Generic.IEnumerable{``0})
ms:mtpsurl: https://technet.microsoft.com/library/Dn968520(v=AX.60)
ms:contentKeyID: 65321135
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateCollectionHash``1
dev_langs:
- CSharp
- C++
- VB
---

# CalculateCollectionHash(T) Method

Calculates the hash of a collection of ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function CalculateCollectionHash(Of T) ( _
    ids As IEnumerable(Of T) _
) As Integer
'Usage
Dim ids As IEnumerable(Of T)
Dim returnValue As Integer

returnValue = DataCacheAccessor.CalculateCollectionHash(ids)
```

``` csharp
protected static int CalculateCollectionHash<T>(
    IEnumerable<T> ids
)
```

``` c++
protected:
generic<typename T>
static int CalculateCollectionHash(
    IEnumerable<T>^ ids
)
```

#### Type Parameters

  - T

#### Parameters

  - ids  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<T\>  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Hash corresponding to this collection of identifiers.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

