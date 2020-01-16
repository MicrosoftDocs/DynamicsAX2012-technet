---
title: LoyaltyCard.PartyRecordId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PartyRecordId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard.PartyRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycard.partyrecordid(v=AX.60)
ms:contentKeyID: 62205653
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard.PartyRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PartyRecordId Property

Gets the record identifier of the party of the card owner.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property PartyRecordId As Long
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As Long

value = instance.PartyRecordId

instance.PartyRecordId = value
```

``` csharp
[IgnoreDataMemberAttribute]
public long PartyRecordId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property long long PartyRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

