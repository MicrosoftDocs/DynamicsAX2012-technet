---
title: Contractor security role (HcmContractor)
TOCTitle: Contractor security role (HcmContractor)
ms:assetid: 09693372-fb05-480c-8190-2269dea29f41
ms:mtpsurl: https://technet.microsoft.com/library/Hh544040(v=AX.60)
ms:contentKeyID: 37823121
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Contractor security role (HcmContractor) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Contractor security role represents a worker who has a contractor relationship with legal entities.

By default, the [Time registration worker security role (JmgAdvTimeWorker)](time-registration-worker-security-role-jmgadvtimeworker.md) is a subordinate role of this security role. This means that when a user is assigned to this security role, they automatically gain access to the duties in the subordinate role, as well.

## Duties

By default, this security role is assigned the following duties in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Duty name</strong></p></th>
<th><p><strong>Duty AOT name</strong></p></th>
<th><p><strong>Duty description</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Inquire into employee information (Enterprise Portal)</p></td>
<td><p>HcmEPEmployeeInquire</p></td>
<td><p>Respond to inquiries about employee information using Enterprise Portal</p></td>
</tr>
<tr class="even">
<td><p>Inquire into signing limit status</p></td>
<td><p>HRPSigningLimitInquire</p></td>
<td><p>Respond to inquiries about status of signing limits</p></td>
</tr>
<tr class="odd">
<td><p>Maintain access to questionnaires (Enterprise Portal)</p></td>
<td><p>HcmEPQuestionnaireMaintain</p></td>
<td><p>Maintain access to questionnaires using Enterprise Portal</p></td>
</tr>
<tr class="even">
<td><p>Maintain employee information (Enterprise Portal)</p></td>
<td><p>HcmEPemployeemaintenance</p></td>
<td><p>Maintain employee information using Enterprise Portal</p></td>
</tr>
<tr class="odd">
<td><p>Maintain organizational access (Enterprise Portal)</p></td>
<td><p>HcmEPOrganizationalMaintain</p></td>
<td><p>Maintain access to organizational information using Enterprise Portal</p></td>
</tr>
<tr class="even">
<td><p>Maintain signing limits</p></td>
<td><p>HRPSigningLimitMaintain</p></td>
<td><p>Respond to inquiries about signing limits</p></td>
</tr>
<tr class="odd">
<td><p>Maintain travel requisitions and expenses</p></td>
<td><p>TrvTravelRequestsAndExpensesMaintain</p></td>
<td><p>Document and record travel requisitions and expenses</p></td>
</tr>
</tbody>
</table>

  


