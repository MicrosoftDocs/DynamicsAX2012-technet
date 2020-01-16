---
title: UnitOfMeasureConversionDataManager.GetUnitsOfMeasure Method (QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetUnitsOfMeasure Method (QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.UnitOfMeasureConversionDataManager.GetUnitsOfMeasure(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.unitofmeasureconversiondatamanager.getunitsofmeasure(v=AX.60)
ms:contentKeyID: 65319327
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetUnitsOfMeasure Method (QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetUnitsOfMeasure ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of UnitOfMeasure)
'Usage
Dim instance As UnitOfMeasureConversionDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of UnitOfMeasure)

returnValue = instance.GetUnitsOfMeasure(settings)
```

``` csharp
public ReadOnlyCollection<UnitOfMeasure> GetUnitsOfMeasure(
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<UnitOfMeasure^>^ GetUnitsOfMeasure(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[UnitOfMeasure](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[UnitOfMeasureConversionDataManager Class](unitofmeasureconversiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetUnitsOfMeasure Overload](unitofmeasureconversiondatamanager-getunitsofmeasure-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

