---
title: DataCacheAccessor.GetKeyPattern Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetKeyPattern Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.GetKeyPattern
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor.getkeypattern(v=AX.60)
ms:contentKeyID: 65319592
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.GetKeyPattern
dev_langs:
- CSharp
- C++
- VB
---

# GetKeyPattern Method

Returns the key pattern specific to each implementation of the memory cache.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride Function GetKeyPattern As String
'Usage
Dim returnValue As String

returnValue = Me.GetKeyPattern()
```

``` csharp
protected abstract string GetKeyPattern()
```

``` c++
protected:
virtual String^ GetKeyPattern() abstract
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
A string which serves as a prefix for all the keys calculated by a given implementation of a memory cache accessor.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

