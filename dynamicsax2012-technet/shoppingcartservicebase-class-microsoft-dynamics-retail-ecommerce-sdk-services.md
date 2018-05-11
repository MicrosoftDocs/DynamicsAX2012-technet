﻿---
title: ShoppingCartServiceBase Class (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ShoppingCartServiceBase Class
ms:assetid: T:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartservicebase(v=AX.60)
ms:contentKeyID: 65317863
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartServiceBase Class

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
Public MustInherit Class ShoppingCartServiceBase _
    Inherits ServiceBase(Of ShoppingCartController) _
    Implements IShoppingCartService
'Usage
Dim instance As ShoppingCartServiceBase
```

``` csharp
[ComVisibleAttribute(false)]
public abstract class ShoppingCartServiceBase : ServiceBase<ShoppingCartController>, 
    IShoppingCartService
```

``` c++
[ComVisibleAttribute(false)]
public ref class ShoppingCartServiceBase abstract : public ServiceBase<ShoppingCartController^>, 
    IShoppingCartService
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)\<[ShoppingCartController](shoppingcartcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)\>  
    Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)
