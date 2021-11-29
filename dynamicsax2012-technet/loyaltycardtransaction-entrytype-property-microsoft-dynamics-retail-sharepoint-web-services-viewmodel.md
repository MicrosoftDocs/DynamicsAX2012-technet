---
title: LoyaltyCardTransaction.EntryType Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: EntryType Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransaction.EntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardtransaction.entrytype(v=AX.60)
ms:contentKeyID: 62207554
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransaction.EntryType
dev_langs:
- CSharp
- C++
- VB
---

# EntryType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the entry type of the reward point, e.g. Earn, Redeem.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EntryType As LoyaltyRewardPointEntryType
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As LoyaltyRewardPointEntryType

value = instance.EntryType
```

``` csharp
[DataMemberAttribute]
public LoyaltyRewardPointEntryType EntryType { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property LoyaltyRewardPointEntryType EntryType {
    LoyaltyRewardPointEntryType get ();
    internal: void set (LoyaltyRewardPointEntryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

