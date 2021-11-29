---
title: UnitOfMeasureConversionDataManager.GetUnitOfMeasureConversions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetUnitOfMeasureConversions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.UnitOfMeasureConversionDataManager.GetUnitOfMeasureConversions(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.unitofmeasureconversiondatamanager.getunitofmeasureconversions(v=AX.60)
ms:contentKeyID: 65316288
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.UnitOfMeasureConversionDataManager.GetUnitOfMeasureConversions
dev_langs:
- CSharp
- C++
- VB
---

# GetUnitOfMeasureConversions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetUnitOfMeasureConversions ( _
    itemUnitConversions As IEnumerable(Of ItemUnitConversion), _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of UnitOfMeasureConversion)
'Usage
Dim instance As UnitOfMeasureConversionDataManager
Dim itemUnitConversions As IEnumerable(Of ItemUnitConversion)
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of UnitOfMeasureConversion)

returnValue = instance.GetUnitOfMeasureConversions(itemUnitConversions, _
    settings)
```

``` csharp
public ReadOnlyCollection<UnitOfMeasureConversion> GetUnitOfMeasureConversions(
    IEnumerable<ItemUnitConversion> itemUnitConversions,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<UnitOfMeasureConversion^>^ GetUnitOfMeasureConversions(
    IEnumerable<ItemUnitConversion^>^ itemUnitConversions, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - itemUnitConversions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnitConversion](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[UnitOfMeasureConversionDataManager Class](unitofmeasureconversiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

