---
title: StockCountDataManager.GetStockCountData Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetStockCountData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.GetStockCountData(Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStockCountDataRequest)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.stockcountdatamanager.getstockcountdata(v=AX.60)
ms:contentKeyID: 65319042
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.GetStockCountData
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountData Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetStockCountData ( _
    request As GetStockCountDataRequest _
) As Response
'Usage
Dim instance As StockCountDataManager
Dim request As GetStockCountDataRequest
Dim returnValue As Response

returnValue = instance.GetStockCountData(request)
```

``` csharp
public Response GetStockCountData(
    GetStockCountDataRequest request
)
```

``` c++
public:
Response^ GetStockCountData(
    GetStockCountDataRequest^ request
)
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStockCountDataRequest](getstockcountdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  

## See Also

#### Reference

[StockCountDataManager Class](stockcountdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

