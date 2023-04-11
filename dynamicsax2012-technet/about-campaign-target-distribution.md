---
title: About campaign target distribution
TOCTitle: About campaign target distribution
ms:assetid: 47c40041-1967-47c3-b0aa-cb002ca4a137
ms:mtpsurl: https://technet.microsoft.com/library/Aa496998(v=AX.60)
ms:contentKeyID: 37832500
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- campaigns
- campaign
- target distribution
audience: Application User
ms.search.region: Global
---

# About campaign target distribution 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The target list members for a call list or campaign are the contacts that are listed in the party record for a person or organization. You can distribute the ownership of target list members to workers in your organization. To distribute ownership, in the **Campaign** form, on the **Targets** FastTab, click **Distribute**, and then select an option.

The following table provides descriptions of the available options.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Distribution option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Responsibilities distribution</strong></p></td>
<td><p>When you select this option, you can distribute the target list members to selected workers, regardless of who is responsible for the prospect, contact, or activity.</p>
<p>You might consider distributing the target list members if you are planning a large and general marketing push.</p>
<p>You can distribute targets to selected workers manually by selecting the responsible workers directly in the <strong>Owner</strong> field for all the listed targets.</p></td>
</tr>
<tr class="even">
<td><p><strong>Clear distribution</strong></p></td>
<td><p>Only targets that have no worker assigned to them are updated when targets are distributed to the workers. If you want to update the complete list of campaign targets or call list targets, you must first clear all current distributions by selecting this option.</p></td>
</tr>
<tr class="odd">
<td><p><strong>By main responsible on prospect</strong></p></td>
<td><p>Workers can have specific responsibilities associated with some prospects. For instance, one worker might be the overall account manager for the prospect, another might be responsible for coordinating all marketing plans, and another might be responsible for service agreements.</p>
<p>You can distribute the call list targets or campaign targets by responsibility to the workers who are associated with the prospect. This ensures that the targets are contacted by the worker who usually is responsible for a certain area or activity, such as sales contacts or service agreements.</p>
<p>If a worker is not registered for the prospect, the target is not updated.</p></td>
</tr>
<tr class="even">
<td><p><strong>By main responsible on customer</strong></p></td>
<td><p>You can distribute the call list targets or campaign targets to the worker who is registered as the employee responsible for the customer. This ensures that the targets are associated with the workers who are responsible for contact with the customer.</p></td>
</tr>
<tr class="odd">
<td><p><strong>By main responsible on vendor</strong></p></td>
<td><p>You can distribute the call list targets or campaign targets to the worker who is registered as the employee responsible for the vendor. This ensures that the targets are associated with the workers who are responsible for contact with the vendor.</p></td>
</tr>
<tr class="even">
<td><p><strong>By main responsible on contact</strong></p></td>
<td><p>You can distribute the call list targets or campaign targets to the worker who is registered as the employee responsible for the contact. This ensures that the targets are associated with the workers who are responsible for contact with the contact.</p>
<p>If a main contact is not registered for the contact, the target is not updated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>By responsibilities on prospect</strong></p></td>
<td><p>You can distribute the call list targets or campaign targets to the worker who is assigned to the selected responsibility for the prospect.</p>
<p>If the responsibility for the prospect is not assigned, the target record is not updated to reflect an owner.</p></td>
</tr>
<tr class="even">
<td><p><strong>By responsibilities on customer</strong></p></td>
<td><p>You can distribute the call list targets or campaign targets to the worker who is assigned to the selected responsibility for the customer.</p>
<p>If the responsibility for the customer is not assigned, the target record is not updated to reflect an owner.</p></td>
</tr>
<tr class="odd">
<td><p><strong>By responsibilities on vendor</strong></p></td>
<td><p>You can distribute the call list targets or campaign targets to the worker who is assigned to the selected responsibility for the vendor.</p>
<p>If the responsibility for the vendor is not assigned, the target record is not updated to reflect an owner.</p></td>
</tr>
</tbody>
</table>


## See also

[Add campaign targets](add-campaign-targets.md)

[Select campaign targets](select-campaign-targets.md)

[Changing campaign target activity data](changing-campaign-target-activity-data.md)

[Combine queries for campaign targets](combine-queries-for-campaign-targets.md)

  


