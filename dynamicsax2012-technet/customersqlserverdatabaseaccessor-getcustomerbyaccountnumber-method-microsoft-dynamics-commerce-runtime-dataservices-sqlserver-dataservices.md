---
title: CustomerSqlServerDatabaseAccessor.GetCustomerByAccountNumber Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices)
TOCTitle: GetCustomerByAccountNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.GetCustomerByAccountNumber(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.customersqlserverdatabaseaccessor.getcustomerbyaccountnumber(v=AX.60)
ms:contentKeyID: 65315807
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.GetCustomerByAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerByAccountNumber Method

Gets the customer by account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerByAccountNumber ( _
    accountNumber As String _
) As Customer
'Usage
Dim instance As CustomerSqlServerDatabaseAccessor
Dim accountNumber As String
Dim returnValue As Customer

returnValue = instance.GetCustomerByAccountNumber(accountNumber)
```

``` csharp
public Customer GetCustomerByAccountNumber(
    string accountNumber
)
```

``` c++
public:
Customer^ GetCustomerByAccountNumber(
    String^ accountNumber
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The customer.  

## See Also

#### Reference

[CustomerSqlServerDatabaseAccessor Class](customersqlserverdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)

