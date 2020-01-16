---
title: ICachedTaxDataManager.PutTaxOverrides Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTaxOverrides Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTaxDataManager.PutTaxOverrides(Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy,System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedtaxdatamanager.puttaxoverrides(v=AX.60)
ms:contentKeyID: 62204517
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTaxDataManager.PutTaxOverrides
dev_langs:
- CSharp
- C++
- VB
---

# PutTaxOverrides Method

Stores the tax overrides per store by code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutTaxOverrides ( _
    overrideBy As TaxOverrideBy, _
    channelId As Long, _
    columns As ColumnSet, _
    result As ReadOnlyCollection(Of TaxOverride) _
)
'Usage
Dim instance As ICachedTaxDataManager
Dim overrideBy As TaxOverrideBy
Dim channelId As Long
Dim columns As ColumnSet
Dim result As ReadOnlyCollection(Of TaxOverride)

instance.PutTaxOverrides(overrideBy, _
    channelId, columns, result)
```

``` csharp
void PutTaxOverrides(
    TaxOverrideBy overrideBy,
    long channelId,
    ColumnSet columns,
    ReadOnlyCollection<TaxOverride> result
)
```

``` c++
void PutTaxOverrides(
    TaxOverrideBy overrideBy, 
    long long channelId, 
    ColumnSet^ columns, 
    ReadOnlyCollection<TaxOverride^>^ result
)
```

#### Parameters

  - overrideBy  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedTaxDataManager Interface](icachedtaxdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

