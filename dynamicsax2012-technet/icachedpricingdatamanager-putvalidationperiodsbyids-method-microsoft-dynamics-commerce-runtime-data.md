---
title: ICachedPricingDataManager.PutValidationPeriodsByIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutValidationPeriodsByIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutValidationPeriodsByIds(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putvalidationperiodsbyids(v=AX.60)
ms:contentKeyID: 62208034
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutValidationPeriodsByIds
dev_langs:
- CSharp
- C++
- VB
---

# PutValidationPeriodsByIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Stores the result of a call to retrieve the the periodic discount validation periods for a given set of identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutValidationPeriodsByIds ( _
    periodIds As IEnumerable(Of String), _
    columns As ColumnSet, _
    result As ReadOnlyCollection(Of ValidationPeriod) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim periodIds As IEnumerable(Of String)
Dim columns As ColumnSet
Dim result As ReadOnlyCollection(Of ValidationPeriod)

instance.PutValidationPeriodsByIds(periodIds, _
    columns, result)
```

``` csharp
void PutValidationPeriodsByIds(
    IEnumerable<string> periodIds,
    ColumnSet columns,
    ReadOnlyCollection<ValidationPeriod> result
)
```

``` c++
void PutValidationPeriodsByIds(
    IEnumerable<String^>^ periodIds, 
    ColumnSet^ columns, 
    ReadOnlyCollection<ValidationPeriod^>^ result
)
```

#### Parameters

  - periodIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ValidationPeriod](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

