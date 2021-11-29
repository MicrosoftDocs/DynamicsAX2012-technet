---
title: CustomerController.SendAccountActivationEmailToCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: SendAccountActivationEmailToCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.SendAccountActivationEmailToCustomer(System.String,System.String,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.sendaccountactivationemailtocustomer(v=AX.60)
ms:contentKeyID: 65317030
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.SendAccountActivationEmailToCustomer
dev_langs:
- CSharp
- C++
- VB
---

# SendAccountActivationEmailToCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub SendAccountActivationEmailToCustomer ( _
    emailAddress As String, _
    emailTemplateId As String, _
    customerName As String, _
    activationUrl As String, _
    activationToken As String, _
    storefrontName As String _
)
'Usage
Dim instance As CustomerController
Dim emailAddress As String
Dim emailTemplateId As String
Dim customerName As String
Dim activationUrl As String
Dim activationToken As String
Dim storefrontName As String

instance.SendAccountActivationEmailToCustomer(emailAddress, _
    emailTemplateId, customerName, activationUrl, _
    activationToken, storefrontName)
```

``` csharp
public virtual void SendAccountActivationEmailToCustomer(
    string emailAddress,
    string emailTemplateId,
    string customerName,
    string activationUrl,
    string activationToken,
    string storefrontName
)
```

``` c++
public:
virtual void SendAccountActivationEmailToCustomer(
    String^ emailAddress, 
    String^ emailTemplateId, 
    String^ customerName, 
    String^ activationUrl, 
    String^ activationToken, 
    String^ storefrontName
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - emailTemplateId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationUrl  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storefrontName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

