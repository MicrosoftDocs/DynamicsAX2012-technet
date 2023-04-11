---
title: LoyaltyCardTransaction.EntryDateTime Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: EntryDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransaction.EntryDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardtransaction.entrydatetime(v=AX.60)
ms:contentKeyID: 62204008
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransaction.EntryDateTime
dev_langs:
- CSharp
- C++
- VB
---

# EntryDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the entry date time of the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EntryDateTime As DateTime
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As DateTime

value = instance.EntryDateTime
```

``` csharp
[DataMemberAttribute]
public DateTime EntryDateTime { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime EntryDateTime {
    DateTime get ();
    internal: void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

