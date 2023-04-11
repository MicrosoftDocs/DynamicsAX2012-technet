---
title: DataCacheAccessor.CalculateColumnSetHash Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CalculateColumnSetHash Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateColumnSetHash(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor.calculatecolumnsethash(v=AX.60)
ms:contentKeyID: 65319142
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateColumnSetHash
dev_langs:
- CSharp
- C++
- VB
---

# CalculateColumnSetHash Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculates the hash of a column set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function CalculateColumnSetHash ( _
    columnSet As ColumnSet _
) As Integer
'Usage
Dim columnSet As ColumnSet
Dim returnValue As Integer

returnValue = DataCacheAccessor.CalculateColumnSetHash(columnSet)
```

``` csharp
protected static int CalculateColumnSetHash(
    ColumnSet columnSet
)
```

``` c++
protected:
static int CalculateColumnSetHash(
    ColumnSet^ columnSet
)
```

#### Parameters

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Hash corresponding to this column set.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

