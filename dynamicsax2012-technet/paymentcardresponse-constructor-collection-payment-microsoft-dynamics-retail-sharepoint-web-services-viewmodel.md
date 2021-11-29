---
title: PaymentCardResponse Constructor (Collection(Payment)) (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PaymentCardResponse Constructor (Collection(Payment))
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardResponse.#ctor(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Payment})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.paymentcardresponse.paymentcardresponse(v=AX.60)
ms:contentKeyID: 62206828
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PaymentCardResponse Constructor (Collection(Payment))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [PaymentCardResponse](paymentcardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md) class with the specified payment card collection.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    paymentCards As Collection(Of Payment) _
)
'Usage
Dim paymentCards As Collection(Of Payment)

Dim instance As New PaymentCardResponse(paymentCards)
```

``` csharp
public PaymentCardResponse(
    Collection<Payment> paymentCards
)
```

``` c++
public:
PaymentCardResponse(
    Collection<Payment^>^ paymentCards
)
```

#### Parameters

  - paymentCards  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[Payment](payment-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

## See Also

#### Reference

[PaymentCardResponse Class](paymentcardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[PaymentCardResponse Overload](paymentcardresponse-constructor-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

