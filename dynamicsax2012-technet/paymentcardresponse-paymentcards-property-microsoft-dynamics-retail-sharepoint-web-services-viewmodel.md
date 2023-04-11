---
title: PaymentCardResponse.PaymentCards Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PaymentCards Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardResponse.PaymentCards
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.paymentcardresponse.paymentcards(v=AX.60)
ms:contentKeyID: 62204192
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardResponse.PaymentCards
dev_langs:
- CSharp
- C++
- VB
---

# PaymentCards Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the demo data.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentCards As Collection(Of Payment)
    Get
    Private Set
'Usage
Dim instance As PaymentCardResponse
Dim value As Collection(Of Payment)

value = instance.PaymentCards
```

``` csharp
[DataMemberAttribute]
public Collection<Payment> PaymentCards { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<Payment^>^ PaymentCards {
    Collection<Payment^>^ get ();
    private: void set (Collection<Payment^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[Payment](payment-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[PaymentCardResponse Class](paymentcardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

