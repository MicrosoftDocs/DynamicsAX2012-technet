---
title: ServiceBase(T) Class (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ServiceBase(T) Class
ms:assetid: T:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn988306(v=AX.60)
ms:contentKeyID: 65317352
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1
dev_langs:
- CSharp
- C++
- VB
---

# ServiceBase(T) Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class ServiceBase(Of T As {New, ControllerBase})
'Usage
Dim instance As ServiceBase(Of T)
```

``` csharp
public abstract class ServiceBase<T>
where T : new(), ControllerBase
```

``` c++
generic<typename T>
where T : gcnew(), ControllerBase
public ref class ServiceBase abstract
```

#### Type Parameters

  - T

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase\<T\>  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ChannelServiceBase](channelservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase](checkoutservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase](customerservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase](loyaltyservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.OrderServiceBase](orderservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase](pricingservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase](shoppingcartservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityServiceBase](storeproductavailabilityservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  
    [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase](wishlistservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

