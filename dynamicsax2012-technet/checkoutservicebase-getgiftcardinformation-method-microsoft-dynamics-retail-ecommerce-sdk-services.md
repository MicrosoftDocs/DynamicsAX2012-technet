---
title: CheckoutServiceBase.GetGiftCardInformation Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetGiftCardInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase.GetGiftCardInformation(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.checkoutservicebase.getgiftcardinformation(v=AX.60)
ms:contentKeyID: 65316949
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase.GetGiftCardInformation
dev_langs:
- CSharp
- C++
- VB
---

# GetGiftCardInformation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetGiftCardInformation ( _
    giftCardId As String _
) As GiftCardResponse
'Usage
Dim instance As CheckoutServiceBase
Dim giftCardId As String
Dim returnValue As GiftCardResponse

returnValue = instance.GetGiftCardInformation(giftCardId)
```

``` csharp
public virtual GiftCardResponse GetGiftCardInformation(
    string giftCardId
)
```

``` c++
public:
virtual GiftCardResponse^ GetGiftCardInformation(
    String^ giftCardId
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.GiftCardResponse](giftcardresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ICheckoutService.GetGiftCardInformation(String)](icheckoutservice-getgiftcardinformation-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CheckoutServiceBase Class](checkoutservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

