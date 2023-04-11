---
title: CustomerController.CreateCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: CreateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.CreateCustomer(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.createcustomer(v=AX.60)
ms:contentKeyID: 65316812
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.CreateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function CreateCustomer ( _
    customer As Customer, _
    userId As String _
) As Customer
'Usage
Dim instance As CustomerController
Dim customer As Customer
Dim userId As String
Dim returnValue As Customer

returnValue = instance.CreateCustomer(customer, _
    userId)
```

``` csharp
public virtual Customer CreateCustomer(
    Customer customer,
    string userId
)
```

``` c++
public:
virtual Customer^ CreateCustomer(
    Customer^ customer, 
    String^ userId
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

