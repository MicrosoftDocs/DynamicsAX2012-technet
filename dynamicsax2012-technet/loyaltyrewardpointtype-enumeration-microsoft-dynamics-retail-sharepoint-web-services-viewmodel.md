---
title: LoyaltyRewardPointType Enumeration (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: LoyaltyRewardPointType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltyrewardpointtype(v=AX.60)
ms:contentKeyID: 62202755
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointType
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointType.None
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointType.Quantity
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPointType.Amount
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyRewardPointType Enumeration

Describes the unit type of the loyalty reward point.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration LoyaltyRewardPointType
'Usage
Dim instance As LoyaltyRewardPointType
```

``` csharp
[DataContractAttribute]
public enum LoyaltyRewardPointType
```

``` c++
[DataContractAttribute]
public enum class LoyaltyRewardPointType
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
<td>The default reward point type. Should not be used.</td>
</tr>
<tr class="even">
<td></td>
<td>Quantity</td>
<td>Quantity type measured by a numeric value.</td>
</tr>
<tr class="odd">
<td></td>
<td>Amount</td>
<td>Amount type measured by a numeric value and a currency code.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailLoyaltyRewardPointType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

