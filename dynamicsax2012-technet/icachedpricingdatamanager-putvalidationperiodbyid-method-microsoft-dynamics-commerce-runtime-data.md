---
title: ICachedPricingDataManager.PutValidationPeriodById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutValidationPeriodById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutValidationPeriodById(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putvalidationperiodbyid(v=AX.60)
ms:contentKeyID: 62209746
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutValidationPeriodById
dev_langs:
- CSharp
- C++
- VB
---

# PutValidationPeriodById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the periodic discount validation period with given identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutValidationPeriodById ( _
    periodId As String, _
    columns As ColumnSet, _
    result As ValidationPeriod _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim periodId As String
Dim columns As ColumnSet
Dim result As ValidationPeriod

instance.PutValidationPeriodById(periodId, _
    columns, result)
```

``` csharp
void PutValidationPeriodById(
    string periodId,
    ColumnSet columns,
    ValidationPeriod result
)
```

``` c++
void PutValidationPeriodById(
    String^ periodId, 
    ColumnSet^ columns, 
    ValidationPeriod^ result
)
```

#### Parameters

  - periodId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

