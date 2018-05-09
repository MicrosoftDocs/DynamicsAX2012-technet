---
title: CustomerController.GetRegisteredCustomerIdByEmailAddress Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetRegisteredCustomerIdByEmailAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.GetRegisteredCustomerIdByEmailAddress(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.getregisteredcustomeridbyemailaddress(v=AX.60)
ms:contentKeyID: 65318340
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.GetRegisteredCustomerIdByEmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# GetRegisteredCustomerIdByEmailAddress Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetRegisteredCustomerIdByEmailAddress ( _
    emailAddress As String _
) As String
'Usage
Dim instance As CustomerController
Dim emailAddress As String
Dim returnValue As String

returnValue = instance.GetRegisteredCustomerIdByEmailAddress(emailAddress)
```

``` csharp
public virtual string GetRegisteredCustomerIdByEmailAddress(
    string emailAddress
)
```

``` c++
public:
virtual String^ GetRegisteredCustomerIdByEmailAddress(
    String^ emailAddress
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

