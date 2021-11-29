---
title: CustomerController.UpdateCustomerAddresses Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: UpdateCustomerAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.UpdateCustomerAddresses(Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.updatecustomeraddresses(v=AX.60)
ms:contentKeyID: 65315636
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.UpdateCustomerAddresses
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomerAddresses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub UpdateCustomerAddresses ( _
    cart As Cart, _
    customerId As String _
)
'Usage
Dim instance As CustomerController
Dim cart As Cart
Dim customerId As String

instance.UpdateCustomerAddresses(cart, _
    customerId)
```

``` csharp
public virtual void UpdateCustomerAddresses(
    Cart cart,
    string customerId
)
```

``` c++
public:
virtual void UpdateCustomerAddresses(
    Cart^ cart, 
    String^ customerId
)
```

#### Parameters

  - cart  
    Type: Cart  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

