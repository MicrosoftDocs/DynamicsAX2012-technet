---
title: GetOrdersRequest Constructor (SalesOrderSearchCriteria, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetOrdersRequest Constructor (SalesOrderSearchCriteria, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOrdersRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getordersrequest.getordersrequest(v=AX.60)
ms:contentKeyID: 65321600
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOrdersRequest Constructor (SalesOrderSearchCriteria, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    criteria As SalesOrderSearchCriteria, _
    settings As QueryResultSettings _
)
'Usage
Dim criteria As SalesOrderSearchCriteria
Dim settings As QueryResultSettings

Dim instance As New GetOrdersRequest(criteria, _
    settings)
```

``` csharp
public GetOrdersRequest(
    SalesOrderSearchCriteria criteria,
    QueryResultSettings settings
)
```

``` c++
public:
GetOrdersRequest(
    SalesOrderSearchCriteria^ criteria, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetOrdersRequest Class](getordersrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetOrdersRequest Overload](getordersrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

