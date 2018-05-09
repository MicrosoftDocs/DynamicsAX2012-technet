---
title: UnitOfMeasureConversionDataManager.GetUnitsOfMeasure Method (IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetUnitsOfMeasure Method (IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.UnitOfMeasureConversionDataManager.GetUnitsOfMeasure(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.unitofmeasureconversiondatamanager.getunitsofmeasure(v=AX.60)
ms:contentKeyID: 62203672
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetUnitsOfMeasure Method (IEnumerable(String))

Retrieves a set of units of measure for the given symbol(s).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetUnitsOfMeasure ( _
    unitIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of UnitOfMeasure)
'Usage
Dim instance As UnitOfMeasureConversionDataManager
Dim unitIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of UnitOfMeasure)

returnValue = instance.GetUnitsOfMeasure(unitIds)
```

``` csharp
public ReadOnlyCollection<UnitOfMeasure> GetUnitsOfMeasure(
    IEnumerable<string> unitIds
)
```

``` c++
public:
ReadOnlyCollection<UnitOfMeasure^>^ GetUnitsOfMeasure(
    IEnumerable<String^>^ unitIds
)
```

#### Parameters

  - unitIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[UnitOfMeasure](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of units of measure for the symbol(s).  

## See Also

#### Reference

[UnitOfMeasureConversionDataManager Class](unitofmeasureconversiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetUnitsOfMeasure Overload](unitofmeasureconversiondatamanager-getunitsofmeasure-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

