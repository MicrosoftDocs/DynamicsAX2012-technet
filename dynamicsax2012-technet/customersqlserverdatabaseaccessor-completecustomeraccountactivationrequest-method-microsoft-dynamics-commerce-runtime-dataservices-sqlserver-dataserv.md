---
title: CustomerSqlServerDatabaseAccessor.CompleteCustomerAccountActivationRequest Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices)
TOCTitle: CompleteCustomerAccountActivationRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.CompleteCustomerAccountActivationRequest(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.customersqlserverdatabaseaccessor.completecustomeraccountactivationrequest(v=AX.60)
ms:contentKeyID: 65318926
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.CompleteCustomerAccountActivationRequest
dev_langs:
- CSharp
- C++
- VB
---

# CompleteCustomerAccountActivationRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Save customer account activation request to channel DB.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Sub CompleteCustomerAccountActivationRequest ( _
    email As String, _
    activationToken As String _
)
'Usage
Dim instance As CustomerSqlServerDatabaseAccessor
Dim email As String
Dim activationToken As String

instance.CompleteCustomerAccountActivationRequest(email, _
    activationToken)
```

``` csharp
public void CompleteCustomerAccountActivationRequest(
    string email,
    string activationToken
)
```

``` c++
public:
void CompleteCustomerAccountActivationRequest(
    String^ email, 
    String^ activationToken
)
```

#### Parameters

  - email  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerSqlServerDatabaseAccessor Class](customersqlserverdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)

