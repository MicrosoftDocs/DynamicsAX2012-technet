---
title: TenderDataLine.PaymentCard Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PaymentCard Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TenderDataLine.PaymentCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.tenderdataline.paymentcard(v=AX.60)
ms:contentKeyID: 62204877
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TenderDataLine.PaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# PaymentCard Property

Gets or sets the card type.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentCard As Payment
    Get
    Set
'Usage
Dim instance As TenderDataLine
Dim value As Payment

value = instance.PaymentCard

instance.PaymentCard = value
```

``` csharp
[DataMemberAttribute]
public Payment PaymentCard { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Payment^ PaymentCard {
    Payment^ get ();
    void set (Payment^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Payment](payment-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [Payment](payment-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[TenderDataLine Class](tenderdataline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

