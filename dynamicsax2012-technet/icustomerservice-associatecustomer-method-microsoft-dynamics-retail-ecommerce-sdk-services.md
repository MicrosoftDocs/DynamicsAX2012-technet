---
title: ICustomerService.AssociateCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: AssociateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICustomerService.AssociateCustomer(System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icustomerservice.associatecustomer(v=AX.60)
ms:contentKeyID: 65316473
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICustomerService.AssociateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# AssociateCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function AssociateCustomer ( _
    email As String, _
    givenName As String, _
    surname As String, _
    userId As String _
) As StringResponse
'Usage
Dim instance As ICustomerService
Dim email As String
Dim givenName As String
Dim surname As String
Dim userId As String
Dim returnValue As StringResponse

returnValue = instance.AssociateCustomer(email, _
    givenName, surname, userId)
```

``` csharp
[OperationContractAttribute]
StringResponse AssociateCustomer(
    string email,
    string givenName,
    string surname,
    string userId
)
```

``` c++
[OperationContractAttribute]
StringResponse^ AssociateCustomer(
    String^ email, 
    String^ givenName, 
    String^ surname, 
    String^ userId
)
```

#### Parameters

  - email  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - givenName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - surname  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StringResponse](stringresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

