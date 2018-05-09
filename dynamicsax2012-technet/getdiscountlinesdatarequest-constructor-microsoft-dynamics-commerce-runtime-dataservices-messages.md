---
title: GetDiscountLinesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetDiscountLinesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountLinesDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLinesQueryCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdiscountlinesdatarequest.getdiscountlinesdatarequest(v=AX.60)
ms:contentKeyID: 65319441
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountLinesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountLinesDataRequest Constructor

Initializes a new instance of the [GetDiscountLinesDataRequest](getdiscountlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    criteria As DiscountLinesQueryCriteria, _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim criteria As DiscountLinesQueryCriteria
Dim queryResultSettings As QueryResultSettings

Dim instance As New GetDiscountLinesDataRequest(criteria, _
    queryResultSettings)
```

``` csharp
public GetDiscountLinesDataRequest(
    DiscountLinesQueryCriteria criteria,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
GetDiscountLinesDataRequest(
    DiscountLinesQueryCriteria^ criteria, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLinesQueryCriteria](discountlinesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetDiscountLinesDataRequest Class](getdiscountlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

