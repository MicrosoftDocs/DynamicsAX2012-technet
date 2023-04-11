---
title: SearchSalesTransactionDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SearchSalesTransactionDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchSalesTransactionDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.searchsalestransactiondatarequest.searchsalestransactiondatarequest(v=AX.60)
ms:contentKeyID: 65320412
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchSalesTransactionDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SearchSalesTransactionDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SearchSalesTransactionDataRequest](searchsalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

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

Dim instance As New SearchSalesTransactionDataRequest(criteria, _
    settings)
```

``` csharp
public SearchSalesTransactionDataRequest(
    SalesOrderSearchCriteria criteria,
    QueryResultSettings settings
)
```

``` c++
public:
SearchSalesTransactionDataRequest(
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

[SearchSalesTransactionDataRequest Class](searchsalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

