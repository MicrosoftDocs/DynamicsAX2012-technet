---
title: SearchSalesTransactionDataRequest.SearchCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SearchCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchSalesTransactionDataRequest.SearchCriteria
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.searchsalestransactiondatarequest.searchcriteria(v=AX.60)
ms:contentKeyID: 65317003
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchSalesTransactionDataRequest.SearchCriteria
dev_langs:
- CSharp
- C++
- VB
---

# SearchCriteria Property

Gets the search criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property SearchCriteria As SalesOrderSearchCriteria
    Get
    Private Set
'Usage
Dim instance As SearchSalesTransactionDataRequest
Dim value As SalesOrderSearchCriteria

value = instance.SearchCriteria
```

``` csharp
public SalesOrderSearchCriteria SearchCriteria { get; private set; }
```

``` c++
public:
property SalesOrderSearchCriteria^ SearchCriteria {
    SalesOrderSearchCriteria^ get ();
    private: void set (SalesOrderSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SearchSalesTransactionDataRequest Class](searchsalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

