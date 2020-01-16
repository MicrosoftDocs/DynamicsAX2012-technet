---
title: LoyaltyCardTransaction.ExpirationDateFriendly Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ExpirationDateFriendly Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransaction.ExpirationDateFriendly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardtransaction.expirationdatefriendly(v=AX.60)
ms:contentKeyID: 62206784
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransaction.ExpirationDateFriendly
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationDateFriendly Property

Gets the expiration date of the earned points.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExpirationDateFriendly As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As String

value = instance.ExpirationDateFriendly
```

``` csharp
[DataMemberAttribute]
public string ExpirationDateFriendly { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ExpirationDateFriendly {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

