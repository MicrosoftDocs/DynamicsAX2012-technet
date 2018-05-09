---
title: IPricingDataManager.GetPriceParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPriceParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetPriceParameters(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager.getpriceparameters(v=AX.60)
ms:contentKeyID: 49837503
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetPriceParameters
dev_langs:
- CSharp
- C++
- VB
---

# GetPriceParameters Method

Retrieves PriceParameters from the database. This indicates which types of trade agreements are active for various combinations of customer and item types

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetPriceParameters ( _
    columns As ColumnSet _
) As PriceParameters
'Usage
Dim instance As IPricingDataManager
Dim columns As ColumnSet
Dim returnValue As PriceParameters

returnValue = instance.GetPriceParameters(columns)
```

``` csharp
PriceParameters GetPriceParameters(
    ColumnSet columns
)
```

``` c++
PriceParameters^ GetPriceParameters(
    ColumnSet^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The first (and only) row in PriceParameters in the database.  

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

