---
title: SalesOrderDataManager.SearchSalesOrders Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SearchSalesOrders Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.SearchSalesOrders(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.searchsalesorders(v=AX.60)
ms:contentKeyID: 65321895
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.SearchSalesOrders
dev_langs:
- CSharp
- C++
- VB
---

# SearchSalesOrders Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function SearchSalesOrders ( _
    settings As QueryResultSettings, _
    criteria As SalesOrderSearchCriteria _
) As IEnumerable(Of SalesOrder)
'Usage
Dim instance As SalesOrderDataManager
Dim settings As QueryResultSettings
Dim criteria As SalesOrderSearchCriteria
Dim returnValue As IEnumerable(Of SalesOrder)

returnValue = instance.SearchSalesOrders(settings, _
    criteria)
```

``` csharp
public IEnumerable<SalesOrder> SearchSalesOrders(
    QueryResultSettings settings,
    SalesOrderSearchCriteria criteria
)
```

``` c++
public:
IEnumerable<SalesOrder^>^ SearchSalesOrders(
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

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

