---
title: CustomerSqlServerDatabaseAccessor.CreateOrUpdateCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices)
TOCTitle: CreateOrUpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.CreateOrUpdateCustomer(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.customersqlserverdatabaseaccessor.createorupdatecustomer(v=AX.60)
ms:contentKeyID: 65321960
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.CreateOrUpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrUpdateCustomer Method

Creates or updates a customer address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function CreateOrUpdateCustomer ( _
    customer As Customer _
) As Customer
'Usage
Dim instance As CustomerSqlServerDatabaseAccessor
Dim customer As Customer
Dim returnValue As Customer

returnValue = instance.CreateOrUpdateCustomer(customer)
```

``` csharp
public Customer CreateOrUpdateCustomer(
    Customer customer
)
```

``` c++
public:
Customer^ CreateOrUpdateCustomer(
    Customer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Updated customer.  

## See Also

#### Reference

[CustomerSqlServerDatabaseAccessor Class](customersqlserverdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)

