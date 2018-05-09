---
title: OrderServiceBase Class (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: OrderServiceBase Class
ms:assetid: T:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.OrderServiceBase
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.orderservicebase(v=AX.60)
ms:contentKeyID: 65317516
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.OrderServiceBase
dev_langs:
- CSharp
- C++
- VB
---

# OrderServiceBase Class

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
Public MustInherit Class OrderServiceBase _
    Inherits ServiceBase(Of OrderController) _
    Implements IOrderService
'Usage
Dim instance As OrderServiceBase
```

``` csharp
[ComVisibleAttribute(false)]
public abstract class OrderServiceBase : ServiceBase<OrderController>, 
    IOrderService
```

``` c++
[ComVisibleAttribute(false)]
public ref class OrderServiceBase abstract : public ServiceBase<OrderController^>, 
    IOrderService
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)\<[OrderController](ordercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)\>  
    Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.OrderServiceBase  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

