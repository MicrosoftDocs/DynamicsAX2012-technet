---
title: PricingDatabaseAccessor.GetValidationPeriodsByIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetValidationPeriodsByIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetValidationPeriodsByIds(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getvalidationperiodsbyids(v=AX.60)
ms:contentKeyID: 62203948
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetValidationPeriodsByIds
dev_langs:
- CSharp
- C++
- VB
---

# GetValidationPeriodsByIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the periodic discount validation periods for a given set of identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetValidationPeriodsByIds ( _
    periodIds As IEnumerable(Of String), _
    columns As ColumnSet _
) As ReadOnlyCollection(Of ValidationPeriod)
'Usage
Dim instance As PricingDatabaseAccessor
Dim periodIds As IEnumerable(Of String)
Dim columns As ColumnSet
Dim returnValue As ReadOnlyCollection(Of ValidationPeriod)

returnValue = instance.GetValidationPeriodsByIds(periodIds, _
    columns)
```

``` csharp
public ReadOnlyCollection<ValidationPeriod> GetValidationPeriodsByIds(
    IEnumerable<string> periodIds,
    ColumnSet columns
)
```

``` c++
public:
ReadOnlyCollection<ValidationPeriod^>^ GetValidationPeriodsByIds(
    IEnumerable<String^>^ periodIds, 
    ColumnSet^ columns
)
```

#### Parameters

  - periodIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ValidationPeriod](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Periodic discount validation periods matching the given set of identifiers. Null if none found.  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

