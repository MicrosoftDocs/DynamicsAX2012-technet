---
title: ICheckoutService.GetDeliveryPreferences Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetDeliveryPreferences Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetDeliveryPreferences
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icheckoutservice.getdeliverypreferences(v=AX.60)
ms:contentKeyID: 65316462
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryPreferences Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetDeliveryPreferences As DeliveryPreferenceResponse
'Usage
Dim instance As ICheckoutService
Dim returnValue As DeliveryPreferenceResponse

returnValue = instance.GetDeliveryPreferences()
```

``` csharp
[OperationContractAttribute]
DeliveryPreferenceResponse GetDeliveryPreferences()
```

``` c++
[OperationContractAttribute]
DeliveryPreferenceResponse^ GetDeliveryPreferences()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryPreferenceResponse](deliverypreferenceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

