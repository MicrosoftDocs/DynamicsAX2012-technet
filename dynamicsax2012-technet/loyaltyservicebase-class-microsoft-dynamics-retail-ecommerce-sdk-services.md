---
title: LoyaltyServiceBase Class (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: LoyaltyServiceBase Class
ms:assetid: T:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.loyaltyservicebase(v=AX.60)
ms:contentKeyID: 65318687
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyServiceBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
Public MustInherit Class LoyaltyServiceBase _
    Inherits ServiceBase(Of LoyaltyController) _
    Implements ILoyaltyService
'Usage
Dim instance As LoyaltyServiceBase
```

``` csharp
[ComVisibleAttribute(false)]
public abstract class LoyaltyServiceBase : ServiceBase<LoyaltyController>, 
    ILoyaltyService
```

``` c++
[ComVisibleAttribute(false)]
public ref class LoyaltyServiceBase abstract : public ServiceBase<LoyaltyController^>, 
    ILoyaltyService
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)\<[LoyaltyController](loyaltycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)\>  
    Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

