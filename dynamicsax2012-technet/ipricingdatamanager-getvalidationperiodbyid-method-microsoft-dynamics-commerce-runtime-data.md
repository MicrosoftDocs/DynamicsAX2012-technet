---
title: IPricingDataManager.GetValidationPeriodById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetValidationPeriodById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetValidationPeriodById(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager.getvalidationperiodbyid(v=AX.60)
ms:contentKeyID: 49851746
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetValidationPeriodById
dev_langs:
- CSharp
- C++
- VB
---

# GetValidationPeriodById Method

Get the periodic discount validation period with given identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetValidationPeriodById ( _
    periodId As String, _
    columns As ColumnSet _
) As ValidationPeriod
'Usage
Dim instance As IPricingDataManager
Dim periodId As String
Dim columns As ColumnSet
Dim returnValue As ValidationPeriod

returnValue = instance.GetValidationPeriodById(periodId, _
    columns)
```

``` csharp
ValidationPeriod GetValidationPeriodById(
    string periodId,
    ColumnSet columns
)
```

``` c++
ValidationPeriod^ GetValidationPeriodById(
    String^ periodId, 
    ColumnSet^ columns
)
```

#### Parameters

  - periodId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Periodic discount validation period matching given identifier. Null if none found.  

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

