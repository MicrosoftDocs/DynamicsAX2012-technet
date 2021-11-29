---
title: ICheckoutService.GetGiftCardInformation Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetGiftCardInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetGiftCardInformation(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icheckoutservice.getgiftcardinformation(v=AX.60)
ms:contentKeyID: 65318252
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.GetGiftCardInformation
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
<OperationContractAttribute> _
Function GetGiftCardInformation ( _
    giftCardId As String _
) As GiftCardResponse
'Usage
Dim instance As ICheckoutService
Dim giftCardId As String
Dim returnValue As GiftCardResponse

returnValue = instance.GetGiftCardInformation(giftCardId)
```

``` csharp
[OperationContractAttribute]
GiftCardResponse GetGiftCardInformation(
    string giftCardId
)
```

``` c++
[OperationContractAttribute]
GiftCardResponse^ GetGiftCardInformation(
    String^ giftCardId
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.GiftCardResponse](giftcardresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

