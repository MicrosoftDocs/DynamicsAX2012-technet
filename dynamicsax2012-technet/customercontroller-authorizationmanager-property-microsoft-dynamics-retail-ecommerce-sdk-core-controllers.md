---
title: CustomerController.AuthorizationManager Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: AuthorizationManager Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.AuthorizationManager
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.customercontroller.authorizationmanager(v=AX.60)
ms:contentKeyID: 65318766
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CustomerController.AuthorizationManager
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizationManager Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Property AuthorizationManager As IAuthorizationManager
    Get
    Private Set
'Usage
Dim value As IAuthorizationManager

value = Me.AuthorizationManager
```

``` csharp
protected IAuthorizationManager AuthorizationManager { get; private set; }
```

``` c++
protected:
property IAuthorizationManager^ AuthorizationManager {
    IAuthorizationManager^ get ();
    private: void set (IAuthorizationManager^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront.IAuthorizationManager](iauthorizationmanager-interface-microsoft-dynamics-retail-ecommerce-sdk-core-storefront.md)  

## See Also

#### Reference

[CustomerController Class](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

