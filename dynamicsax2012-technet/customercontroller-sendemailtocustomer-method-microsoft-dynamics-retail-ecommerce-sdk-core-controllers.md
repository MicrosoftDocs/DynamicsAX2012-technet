---
title: CustomerController.SendEmailToCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: SendEmailToCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.SendEmailToCustomer(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.sendemailtocustomer(v=AX.60)
ms:contentKeyID: 65317188
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.SendEmailToCustomer
dev_langs:
- CSharp
- C++
- VB
---

# SendEmailToCustomer Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub SendEmailToCustomer ( _
    customerId As String, _
    templateId As String, _
    activationUrl As String _
)
'Usage
Dim instance As CustomerController
Dim customerId As String
Dim templateId As String
Dim activationUrl As String

instance.SendEmailToCustomer(customerId, _
    templateId, activationUrl)
```

``` csharp
public virtual void SendEmailToCustomer(
    string customerId,
    string templateId,
    string activationUrl
)
```

``` c++
public:
virtual void SendEmailToCustomer(
    String^ customerId, 
    String^ templateId, 
    String^ activationUrl
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - templateId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationUrl  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

