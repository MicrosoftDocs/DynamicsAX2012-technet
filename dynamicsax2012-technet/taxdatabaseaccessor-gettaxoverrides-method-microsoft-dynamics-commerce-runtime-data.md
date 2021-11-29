---
title: TaxDatabaseAccessor.GetTaxOverrides Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxOverrides Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor.GetTaxOverrides(Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy,System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxdatabaseaccessor.gettaxoverrides(v=AX.60)
ms:contentKeyID: 62214299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor.GetTaxOverrides
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxOverrides Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax overrides.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxOverrides ( _
    overrideBy As TaxOverrideBy, _
    channelId As Long, _
    columns As ColumnSet _
) As ReadOnlyCollection(Of TaxOverride)
'Usage
Dim instance As TaxDatabaseAccessor
Dim overrideBy As TaxOverrideBy
Dim channelId As Long
Dim columns As ColumnSet
Dim returnValue As ReadOnlyCollection(Of TaxOverride)

returnValue = instance.GetTaxOverrides(overrideBy, _
    channelId, columns)
```

``` csharp
public ReadOnlyCollection<TaxOverride> GetTaxOverrides(
    TaxOverrideBy overrideBy,
    long channelId,
    ColumnSet columns
)
```

``` c++
public:
virtual ReadOnlyCollection<TaxOverride^>^ GetTaxOverrides(
    TaxOverrideBy overrideBy, 
    long long channelId, 
    ColumnSet^ columns
) sealed
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

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of tax override per channel.  

#### Implements

[ITaxDataManager.GetTaxOverrides(TaxOverrideBy, Int64, ColumnSet)](itaxdatamanager-gettaxoverrides-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[TaxDatabaseAccessor Class](taxdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

