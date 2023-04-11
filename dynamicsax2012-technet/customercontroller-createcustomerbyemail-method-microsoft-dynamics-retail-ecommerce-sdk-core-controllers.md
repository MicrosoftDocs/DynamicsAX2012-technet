---
title: CustomerController.CreateCustomerByEmail Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: CreateCustomerByEmail Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.CreateCustomerByEmail(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.createcustomerbyemail(v=AX.60)
ms:contentKeyID: 65318097
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.CreateCustomerByEmail
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomerByEmail Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function CreateCustomerByEmail ( _
    emailAddress As String, _
    activationToken As String, _
    userId As String _
) As Customer
'Usage
Dim instance As CustomerController
Dim emailAddress As String
Dim activationToken As String
Dim userId As String
Dim returnValue As Customer

returnValue = instance.CreateCustomerByEmail(emailAddress, _
    activationToken, userId)
```

``` csharp
public virtual Customer CreateCustomerByEmail(
    string emailAddress,
    string activationToken,
    string userId
)
```

``` c++
public:
virtual Customer^ CreateCustomerByEmail(
    String^ emailAddress, 
    String^ activationToken, 
    String^ userId
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

