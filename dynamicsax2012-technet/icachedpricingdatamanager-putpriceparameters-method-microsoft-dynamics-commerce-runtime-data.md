---
title: ICachedPricingDataManager.PutPriceParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutPriceParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutPriceParameters(Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putpriceparameters(v=AX.60)
ms:contentKeyID: 62203132
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutPriceParameters
dev_langs:
- CSharp
- C++
- VB
---

# PutPriceParameters Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves PriceParameters from the database. This indicates which types of trade agreements are active for various combinations of customer and item types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutPriceParameters ( _
    columns As ColumnSet, _
    result As PriceParameters _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim columns As ColumnSet
Dim result As PriceParameters

instance.PutPriceParameters(columns, _
    result)
```

``` csharp
void PutPriceParameters(
    ColumnSet columns,
    PriceParameters result
)
```

``` c++
void PutPriceParameters(
    ColumnSet^ columns, 
    PriceParameters^ result
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

