---
title: GetSalesLinesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetSalesLinesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesLinesDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLinesQueryCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getsaleslinesdatarequest.getsaleslinesdatarequest(v=AX.60)
ms:contentKeyID: 65321490
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesLinesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesLinesDataRequest Constructor

Initializes a new instance of the [GetSalesLinesDataRequest](getsaleslinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    criteria As SalesLinesQueryCriteria, _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim criteria As SalesLinesQueryCriteria
Dim queryResultSettings As QueryResultSettings

Dim instance As New GetSalesLinesDataRequest(criteria, _
    queryResultSettings)
```

``` csharp
public GetSalesLinesDataRequest(
    SalesLinesQueryCriteria criteria,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
GetSalesLinesDataRequest(
    SalesLinesQueryCriteria^ criteria, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLinesQueryCriteria](saleslinesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetSalesLinesDataRequest Class](getsaleslinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

