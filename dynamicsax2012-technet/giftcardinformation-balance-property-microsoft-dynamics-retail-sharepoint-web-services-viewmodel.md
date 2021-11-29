---
title: GiftCardInformation.Balance Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Balance Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardInformation.Balance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.giftcardinformation.balance(v=AX.60)
ms:contentKeyID: 62205619
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardInformation.Balance
dev_langs:
- CSharp
- C++
- VB
---

# Balance Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the gift card balance.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Balance As Decimal
    Get
    Set
'Usage
Dim instance As GiftCardInformation
Dim value As Decimal

value = instance.Balance

instance.Balance = value
```

``` csharp
[DataMemberAttribute]
public decimal Balance { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Balance {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[GiftCardInformation Class](giftcardinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

