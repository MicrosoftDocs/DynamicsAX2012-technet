---
title: ProductManager.GetUnitsOfMeasure Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetUnitsOfMeasure Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetUnitsOfMeasure(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getunitsofmeasure(v=AX.60)
ms:contentKeyID: 65318844
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetUnitsOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# GetUnitsOfMeasure Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetUnitsOfMeasure ( _
    settings As QueryResultSettings _
) As PagedResult(Of UnitOfMeasure)
'Usage
Dim instance As ProductManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of UnitOfMeasure)

returnValue = instance.GetUnitsOfMeasure(settings)
```

``` csharp
public PagedResult<UnitOfMeasure> GetUnitsOfMeasure(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<UnitOfMeasure^>^ GetUnitsOfMeasure(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[UnitOfMeasure](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

