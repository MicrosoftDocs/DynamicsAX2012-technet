---
title: CustomerSqlServerDatabaseAccessor.SaveCustomerAccountActivationRequest Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices)
TOCTitle: SaveCustomerAccountActivationRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.SaveCustomerAccountActivationRequest(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.customersqlserverdatabaseaccessor.savecustomeraccountactivationrequest(v=AX.60)
ms:contentKeyID: 65315503
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.CustomerSqlServerDatabaseAccessor.SaveCustomerAccountActivationRequest
dev_langs:
- CSharp
- C++
- VB
---

# SaveCustomerAccountActivationRequest Method

Save customer account activation request to channel DB.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Sub SaveCustomerAccountActivationRequest ( _
    email As String, _
    activationToken As String _
)
'Usage
Dim instance As CustomerSqlServerDatabaseAccessor
Dim email As String
Dim activationToken As String

instance.SaveCustomerAccountActivationRequest(email, _
    activationToken)
```

``` csharp
public void SaveCustomerAccountActivationRequest(
    string email,
    string activationToken
)
```

``` c++
public:
void SaveCustomerAccountActivationRequest(
    String^ email, 
    String^ activationToken
)
```

#### Parameters

  - email  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerSqlServerDatabaseAccessor Class](customersqlserverdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)

