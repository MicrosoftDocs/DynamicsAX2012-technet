---
title: CustomerSqlServerDatabaseAccessor.SearchCustomers Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices)
TOCTitle: SearchCustomers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.SearchCustomers(System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.customersqlserverdatabaseaccessor.searchcustomers(v=AX.60)
ms:contentKeyID: 65323050
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.SearchCustomers
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomers Method

Gets the customers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function SearchCustomers ( _
    keyword As String, _
    onlyCurrentCompany As Boolean, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of GlobalCustomer)
'Usage
Dim instance As CustomerSqlServerDatabaseAccessor
Dim keyword As String
Dim onlyCurrentCompany As Boolean
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of GlobalCustomer)

returnValue = instance.SearchCustomers(keyword, _
    onlyCurrentCompany, settings)
```

``` csharp
public ReadOnlyCollection<GlobalCustomer> SearchCustomers(
    string keyword,
    bool onlyCurrentCompany,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<GlobalCustomer^>^ SearchCustomers(
    String^ keyword, 
    bool onlyCurrentCompany, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - keyword  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - onlyCurrentCompany  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[GlobalCustomer](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of customers.  

## See Also

#### Reference

[CustomerSqlServerDatabaseAccessor Class](customersqlserverdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)

