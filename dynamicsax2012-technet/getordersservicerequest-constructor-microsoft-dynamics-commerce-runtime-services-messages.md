---
title: GetOrdersServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetOrdersServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrdersServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getordersservicerequest.getordersservicerequest(v=AX.60)
ms:contentKeyID: 65316123
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrdersServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetOrdersServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

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

Dim instance As New GetOrdersServiceRequest(criteria, _
    settings)
```

``` csharp
public GetOrdersServiceRequest(
    SalesOrderSearchCriteria criteria,
    QueryResultSettings settings
)
```

``` c++
public:
GetOrdersServiceRequest(
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

[GetOrdersServiceRequest Class](getordersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

