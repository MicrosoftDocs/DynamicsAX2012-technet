---
title: LoyaltyRewardPointEntryType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyRewardPointEntryType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointentrytype(v=AX.60)
ms:contentKeyID: 62202260
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType.Earn
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType.Redeem
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType.Refund
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType.Adjust
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType.ReturnEarned
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyRewardPointEntryType Enumeration

Describes the entry type of the loyalty reward point line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

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
<tr class="even">
<td></td>
<td>ReturnEarned</td>
<td>Return earned reward points.</td>
</tr>
<tr class="odd">
<td></td>
<td>Adjust</td>
<td>Adjust reward points.</td>
</tr>
<tr class="even">
<td></td>
<td>Refund</td>
<td>Refund reward points.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailLoyaltyRewardPointEntryType base enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

