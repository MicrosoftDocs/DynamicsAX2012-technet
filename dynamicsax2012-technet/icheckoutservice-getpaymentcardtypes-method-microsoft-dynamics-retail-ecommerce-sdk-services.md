---
title: ICheckoutService.GetPaymentCardTypes Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetPaymentCardTypes Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetPaymentCardTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icheckoutservice.getpaymentcardtypes(v=AX.60)
ms:contentKeyID: 65316670
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetPaymentCardTypes
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentCardTypes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetPaymentCardTypes As PaymentCardTypesResponse
'Usage
Dim instance As ICheckoutService
Dim returnValue As PaymentCardTypesResponse

returnValue = instance.GetPaymentCardTypes()
```

``` csharp
[OperationContractAttribute]
PaymentCardTypesResponse GetPaymentCardTypes()
```

``` c++
[OperationContractAttribute]
PaymentCardTypesResponse^ GetPaymentCardTypes()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PaymentCardTypesResponse](paymentcardtypesresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

