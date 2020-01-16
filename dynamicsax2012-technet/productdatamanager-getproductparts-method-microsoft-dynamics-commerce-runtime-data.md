---
title: ProductDataManager.GetProductParts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductParts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetProductParts(Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.getproductparts(v=AX.60)
ms:contentKeyID: 65320908
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetProductParts
dev_langs:
- CSharp
- C++
- VB
---

# GetProductParts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductParts ( _
    request As GetProductPartsDataServiceRequest _
) As GetProductPartsDataServiceResponse
'Usage
Dim instance As ProductDataManager
Dim request As GetProductPartsDataServiceRequest
Dim returnValue As GetProductPartsDataServiceResponse

returnValue = instance.GetProductParts(request)
```

``` csharp
public GetProductPartsDataServiceResponse GetProductParts(
    GetProductPartsDataServiceRequest request
)
```

``` c++
public:
GetProductPartsDataServiceResponse^ GetProductParts(
    GetProductPartsDataServiceRequest^ request
)
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest](getproductpartsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

