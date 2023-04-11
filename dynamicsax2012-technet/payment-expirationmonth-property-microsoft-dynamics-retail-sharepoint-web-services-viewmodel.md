---
title: Payment.ExpirationMonth Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ExpirationMonth Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Payment.ExpirationMonth
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.payment.expirationmonth(v=AX.60)
ms:contentKeyID: 62204859
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Payment.ExpirationMonth
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationMonth Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the card expiration month.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExpirationMonth As Integer
    Get
    Set
'Usage
Dim instance As Payment
Dim value As Integer

value = instance.ExpirationMonth

instance.ExpirationMonth = value
```

``` csharp
[DataMemberAttribute]
public int ExpirationMonth { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ExpirationMonth {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Payment Class](payment-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

