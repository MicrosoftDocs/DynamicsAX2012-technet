---
title: OrderManager.SearchOrders Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SearchOrders Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.SearchOrders(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.searchorders(v=AX.60)
ms:contentKeyID: 65318508
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.SearchOrders
dev_langs:
- CSharp
- C++
- VB
---

# SearchOrders Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SearchOrders ( _
    settings As QueryResultSettings, _
    criteria As SalesOrderSearchCriteria _
) As PagedResult(Of SalesOrder)
'Usage
Dim instance As OrderManager
Dim settings As QueryResultSettings
Dim criteria As SalesOrderSearchCriteria
Dim returnValue As PagedResult(Of SalesOrder)

returnValue = instance.SearchOrders(settings, _
    criteria)
```

``` csharp
public PagedResult<SalesOrder> SearchOrders(
    QueryResultSettings settings,
    SalesOrderSearchCriteria criteria
)
```

``` c++
public:
PagedResult<SalesOrder^>^ SearchOrders(
    QueryResultSettings^ settings, 
    SalesOrderSearchCriteria^ criteria
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

