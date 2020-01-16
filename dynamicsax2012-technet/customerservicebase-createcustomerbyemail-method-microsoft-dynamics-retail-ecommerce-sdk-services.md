---
title: CustomerServiceBase.CreateCustomerByEmail Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CreateCustomerByEmail Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.CreateCustomerByEmail(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.customerservicebase.createcustomerbyemail(v=AX.60)
ms:contentKeyID: 65315577
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.CreateCustomerByEmail
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomerByEmail Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function CreateCustomerByEmail ( _
    emailAddress As String, _
    activationToken As String _
) As CustomerResponse
'Usage
Dim instance As CustomerServiceBase
Dim emailAddress As String
Dim activationToken As String
Dim returnValue As CustomerResponse

returnValue = instance.CreateCustomerByEmail(emailAddress, _
    activationToken)
```

``` csharp
public virtual CustomerResponse CreateCustomerByEmail(
    string emailAddress,
    string activationToken
)
```

``` c++
public:
virtual CustomerResponse^ CreateCustomerByEmail(
    String^ emailAddress, 
    String^ activationToken
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerResponse](customerresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ICustomerService.CreateCustomerByEmail(String, String)](icustomerservice-createcustomerbyemail-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CustomerServiceBase Class](customerservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

