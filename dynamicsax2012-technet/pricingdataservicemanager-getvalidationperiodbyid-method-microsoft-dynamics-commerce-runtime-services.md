---
title: PricingDataServiceManager.GetValidationPeriodById Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetValidationPeriodById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetValidationPeriodById(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getvalidationperiodbyid(v=AX.60)
ms:contentKeyID: 65319584
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetValidationPeriodById
dev_langs:
- CSharp
- C++
- VB
---

# GetValidationPeriodById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetValidationPeriodById ( _
    periodId As String, _
    columns As ColumnSet _
) As ValidationPeriod
'Usage
Dim instance As PricingDataServiceManager
Dim periodId As String
Dim columns As ColumnSet
Dim returnValue As ValidationPeriod

returnValue = instance.GetValidationPeriodById(periodId, _
    columns)
```

``` csharp
public ValidationPeriod GetValidationPeriodById(
    string periodId,
    ColumnSet columns
)
```

``` c++
public:
virtual ValidationPeriod^ GetValidationPeriodById(
    String^ periodId, 
    ColumnSet^ columns
) sealed
```

#### Parameters

  - periodId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[IPricingDataManager.GetValidationPeriodById(String, ColumnSet)](ipricingdatamanager-getvalidationperiodbyid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

