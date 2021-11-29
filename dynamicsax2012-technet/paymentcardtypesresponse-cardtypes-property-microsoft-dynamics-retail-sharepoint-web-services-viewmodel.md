---
title: PaymentCardTypesResponse.CardTypes Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: CardTypes Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardTypesResponse.CardTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.paymentcardtypesresponse.cardtypes(v=AX.60)
ms:contentKeyID: 62201943
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardTypesResponse.CardTypes
dev_langs:
- CSharp
- C++
- VB
---

# CardTypes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the demo data.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTypes As Collection(Of PaymentCardType)
    Get
    Private Set
'Usage
Dim instance As PaymentCardTypesResponse
Dim value As Collection(Of PaymentCardType)

value = instance.CardTypes
```

``` csharp
[DataMemberAttribute]
public Collection<PaymentCardType> CardTypes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<PaymentCardType^>^ CardTypes {
    Collection<PaymentCardType^>^ get ();
    private: void set (Collection<PaymentCardType^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[PaymentCardType](paymentcardtype-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[PaymentCardTypesResponse Class](paymentcardtypesresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

