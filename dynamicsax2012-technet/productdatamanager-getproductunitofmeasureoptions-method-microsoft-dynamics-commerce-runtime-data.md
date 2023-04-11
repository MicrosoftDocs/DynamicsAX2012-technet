---
title: ProductDataManager.GetProductUnitofMeasureOptions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductUnitofMeasureOptions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetProductUnitofMeasureOptions(Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.getproductunitofmeasureoptions(v=AX.60)
ms:contentKeyID: 65318696
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetProductUnitofMeasureOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetProductUnitofMeasureOptions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductUnitofMeasureOptions ( _
    request As GetProductUnitOfMeasureOptionsDataRequest _
) As GetProductUnitOfMeasureOptionsDataResponse
'Usage
Dim instance As ProductDataManager
Dim request As GetProductUnitOfMeasureOptionsDataRequest
Dim returnValue As GetProductUnitOfMeasureOptionsDataResponse

returnValue = instance.GetProductUnitofMeasureOptions(request)
```

``` csharp
public GetProductUnitOfMeasureOptionsDataResponse GetProductUnitofMeasureOptions(
    GetProductUnitOfMeasureOptionsDataRequest request
)
```

``` c++
public:
GetProductUnitOfMeasureOptionsDataResponse^ GetProductUnitofMeasureOptions(
    GetProductUnitOfMeasureOptionsDataRequest^ request
)
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataRequest](getproductunitofmeasureoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataResponse](getproductunitofmeasureoptionsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

