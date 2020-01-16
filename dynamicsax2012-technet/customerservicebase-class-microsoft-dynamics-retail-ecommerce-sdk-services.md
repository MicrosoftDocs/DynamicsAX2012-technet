---
title: CustomerServiceBase Class (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CustomerServiceBase Class
ms:assetid: T:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.customerservicebase(v=AX.60)
ms:contentKeyID: 65315802
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase
dev_langs:
- CSharp
- C++
- VB
---

# CustomerServiceBase Class

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
Public MustInherit Class CustomerServiceBase _
    Inherits ServiceBase(Of CustomerController) _
    Implements ICustomerService
'Usage
Dim instance As CustomerServiceBase
```

``` csharp
[ComVisibleAttribute(false)]
public abstract class CustomerServiceBase : ServiceBase<CustomerController>, 
    ICustomerService
```

``` c++
[ComVisibleAttribute(false)]
public ref class CustomerServiceBase abstract : public ServiceBase<CustomerController^>, 
    ICustomerService
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)\<[CustomerController](customercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)\>  
    Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

