---
title: Payment.PaymentAddress Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PaymentAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Payment.PaymentAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.payment.paymentaddress(v=AX.60)
ms:contentKeyID: 62207485
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Payment.PaymentAddress
dev_langs:
- CSharp
- C++
- VB
---

# PaymentAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the payment address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentAddress As Address
    Get
    Friend Set
'Usage
Dim instance As Payment
Dim value As Address

value = instance.PaymentAddress
```

``` csharp
[DataMemberAttribute]
public Address PaymentAddress { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ PaymentAddress {
    Address^ get ();
    internal: void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[Payment Class](payment-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

