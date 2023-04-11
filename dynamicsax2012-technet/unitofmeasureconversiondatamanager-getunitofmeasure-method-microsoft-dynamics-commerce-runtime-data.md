---
title: UnitOfMeasureConversionDataManager.GetUnitOfMeasure Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetUnitOfMeasure Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.UnitOfMeasureConversionDataManager.GetUnitOfMeasure(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.unitofmeasureconversiondatamanager.getunitofmeasure(v=AX.60)
ms:contentKeyID: 62213699
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.UnitOfMeasureConversionDataManager.GetUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# GetUnitOfMeasure Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves the UnitOfMeasure for the given symbol.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetUnitOfMeasure ( _
    unitId As String _
) As UnitOfMeasure
'Usage
Dim instance As UnitOfMeasureConversionDataManager
Dim unitId As String
Dim returnValue As UnitOfMeasure

returnValue = instance.GetUnitOfMeasure(unitId)
```

``` csharp
public UnitOfMeasure GetUnitOfMeasure(
    string unitId
)
```

``` c++
public:
UnitOfMeasure^ GetUnitOfMeasure(
    String^ unitId
)
```

#### Parameters

  - unitId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasure](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A unit of measure for the symbol.  

## See Also

#### Reference

[UnitOfMeasureConversionDataManager Class](unitofmeasureconversiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

