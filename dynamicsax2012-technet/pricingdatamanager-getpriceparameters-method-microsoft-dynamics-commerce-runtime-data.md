---
title: PricingDataManager.GetPriceParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPriceParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetPriceParameters(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.getpriceparameters(v=AX.60)
ms:contentKeyID: 49836127
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetPriceParameters
dev_langs:
- CSharp
- C++
- VB
---

# GetPriceParameters Method

Retrieves PriceParameters from the database. This indicates which types of trade agreements are active for various combinations of customer and item types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetPriceParameters ( _
    columns As ColumnSet _
) As PriceParameters
'Usage
Dim instance As PricingDataManager
Dim columns As ColumnSet
Dim returnValue As PriceParameters

returnValue = instance.GetPriceParameters(columns)
```

``` csharp
public PriceParameters GetPriceParameters(
    ColumnSet columns
)
```

``` c++
public:
virtual PriceParameters^ GetPriceParameters(
    ColumnSet^ columns
) sealed
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The first (and only) row in PriceParameters in the database.  

#### Implements

[IPricingDataManager.GetPriceParameters(ColumnSet)](ipricingdatamanager-getpriceparameters-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

