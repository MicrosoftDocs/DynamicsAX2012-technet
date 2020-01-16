---
title: LoyaltyRewardPointEntryType Enumeration (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: LoyaltyRewardPointEntryType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointEntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltyrewardpointentrytype(v=AX.60)
ms:contentKeyID: 62204064
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointEntryType
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointEntryType.Earn
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointEntryType.None
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointEntryType.Redeem
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyRewardPointEntryType Enumeration

Describes the entry type of the loyalty reward point line.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration LoyaltyRewardPointEntryType
'Usage
Dim instance As LoyaltyRewardPointEntryType
```

``` csharp
[DataContractAttribute]
public enum LoyaltyRewardPointEntryType
```

``` c++
[DataContractAttribute]
public enum class LoyaltyRewardPointEntryType
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>The default entry type. Should not be used.</td>
</tr>
<tr class="even">
<td></td>
<td>Earn</td>
<td>Earn reward points.</td>
</tr>
<tr class="odd">
<td></td>
<td>Redeem</td>
<td>Redeem reward points.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailLoyaltyRewardPointEntryType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

