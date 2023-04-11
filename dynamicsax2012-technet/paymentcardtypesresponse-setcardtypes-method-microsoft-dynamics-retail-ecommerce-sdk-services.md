---
title: PaymentCardTypesResponse.SetCardTypes Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SetCardTypes Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PaymentCardTypesResponse.SetCardTypes(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.PaymentCardType})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.paymentcardtypesresponse.setcardtypes(v=AX.60)
ms:contentKeyID: 65316760
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PaymentCardTypesResponse.SetCardTypes
dev_langs:
- CSharp
- C++
- VB
---

# SetCardTypes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub SetCardTypes ( _
    cardTypes As Collection(Of PaymentCardType) _
)
'Usage
Dim instance As PaymentCardTypesResponse
Dim cardTypes As Collection(Of PaymentCardType)

instance.SetCardTypes(cardTypes)
```

``` csharp
public void SetCardTypes(
    Collection<PaymentCardType> cardTypes
)
```

``` c++
public:
void SetCardTypes(
    Collection<PaymentCardType^>^ cardTypes
)
```

#### Parameters

  - cardTypes  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[PaymentCardType](paymentcardtype-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[PaymentCardTypesResponse Class](paymentcardtypesresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

