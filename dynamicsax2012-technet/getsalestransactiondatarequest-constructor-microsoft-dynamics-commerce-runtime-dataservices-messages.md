---
title: GetSalesTransactionDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetSalesTransactionDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTransactionDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getsalestransactiondatarequest.getsalestransactiondatarequest(v=AX.60)
ms:contentKeyID: 65320943
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTransactionDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesTransactionDataRequest Constructor

Initializes a new instance of the [GetSalesTransactionDataRequest](getsalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

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

Dim instance As New GetSalesTransactionDataRequest(criteria, _
    settings)
```

``` csharp
public GetSalesTransactionDataRequest(
    SalesOrderSearchCriteria criteria,
    QueryResultSettings settings
)
```

``` c++
public:
GetSalesTransactionDataRequest(
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

[GetSalesTransactionDataRequest Class](getsalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

