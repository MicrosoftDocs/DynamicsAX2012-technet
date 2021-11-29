---
title: CustomerController.CreateUserCustomerMap Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: CreateUserCustomerMap Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.CreateUserCustomerMap(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.createusercustomermap(v=AX.60)
ms:contentKeyID: 65317490
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.CreateUserCustomerMap
dev_langs:
- CSharp
- C++
- VB
---

# CreateUserCustomerMap Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub CreateUserCustomerMap ( _
    dmCustomer As Customer, _
    userId As String _
)
'Usage
Dim dmCustomer As Customer
Dim userId As String

Me.CreateUserCustomerMap(dmCustomer, _
    userId)
```

``` csharp
protected virtual void CreateUserCustomerMap(
    Customer dmCustomer,
    string userId
)
```

``` c++
protected:
virtual void CreateUserCustomerMap(
    Customer^ dmCustomer, 
    String^ userId
)
```

#### Parameters

  - dmCustomer  
    Type: Customer  

<!-- end list -->

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

