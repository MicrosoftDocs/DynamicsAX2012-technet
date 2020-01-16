---
title: PricingServiceBase Class (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: PricingServiceBase Class
ms:assetid: T:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.pricingservicebase(v=AX.60)
ms:contentKeyID: 65316601
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase
dev_langs:
- CSharp
- C++
- VB
---

# PricingServiceBase Class

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
Public MustInherit Class PricingServiceBase _
    Inherits ServiceBase(Of PricingController) _
    Implements IPricingService
'Usage
Dim instance As PricingServiceBase
```

``` csharp
[ComVisibleAttribute(false)]
public abstract class PricingServiceBase : ServiceBase<PricingController>, 
    IPricingService
```

``` c++
[ComVisibleAttribute(false)]
public ref class PricingServiceBase abstract : public ServiceBase<PricingController^>, 
    IPricingService
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)\<[PricingController](pricingcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)\>  
    Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

