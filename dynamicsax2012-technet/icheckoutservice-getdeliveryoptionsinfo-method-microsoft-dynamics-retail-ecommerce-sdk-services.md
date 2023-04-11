---
title: ICheckoutService.GetDeliveryOptionsInfo Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetDeliveryOptionsInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetDeliveryOptionsInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icheckoutservice.getdeliveryoptionsinfo(v=AX.60)
ms:contentKeyID: 65315767
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetDeliveryOptionsInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryOptionsInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetDeliveryOptionsInfo As DeliveryOptionsResponse
'Usage
Dim instance As ICheckoutService
Dim returnValue As DeliveryOptionsResponse

returnValue = instance.GetDeliveryOptionsInfo()
```

``` csharp
[OperationContractAttribute]
DeliveryOptionsResponse GetDeliveryOptionsInfo()
```

``` c++
[OperationContractAttribute]
DeliveryOptionsResponse^ GetDeliveryOptionsInfo()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

