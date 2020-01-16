---
title: TaxL2CacheDataStoreAccessor.GetKeyPattern Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetKeyPattern Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetKeyPattern
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.getkeypattern(v=AX.60)
ms:contentKeyID: 62210635
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetKeyPattern
dev_langs:
- CSharp
- C++
- VB
---

# GetKeyPattern Method

Returns a prefix of the caching key common to instances of this class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKeyPattern As String
'Usage
Dim returnValue As String

returnValue = Me.GetKeyPattern()
```

``` csharp
protected override string GetKeyPattern()
```

``` c++
protected:
virtual String^ GetKeyPattern() override
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
A prefix of the caching key common to instances of this class.  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

