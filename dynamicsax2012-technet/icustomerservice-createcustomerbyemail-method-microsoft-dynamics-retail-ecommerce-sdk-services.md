---
title: ICustomerService.CreateCustomerByEmail Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CreateCustomerByEmail Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICustomerService.CreateCustomerByEmail(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icustomerservice.createcustomerbyemail(v=AX.60)
ms:contentKeyID: 65316033
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICustomerService.CreateCustomerByEmail
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomerByEmail Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function CreateCustomerByEmail ( _
    emailAddress As String, _
    activationToken As String _
) As CustomerResponse
'Usage
Dim instance As ICustomerService
Dim emailAddress As String
Dim activationToken As String
Dim returnValue As CustomerResponse

returnValue = instance.CreateCustomerByEmail(emailAddress, _
    activationToken)
```

``` csharp
[OperationContractAttribute]
CustomerResponse CreateCustomerByEmail(
    string emailAddress,
    string activationToken
)
```

``` c++
[OperationContractAttribute]
CustomerResponse^ CreateCustomerByEmail(
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

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

