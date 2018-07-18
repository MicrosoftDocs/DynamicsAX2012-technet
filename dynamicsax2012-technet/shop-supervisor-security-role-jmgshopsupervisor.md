---
title: Shop supervisor security role (JmgShopSupervisor)
TOCTitle: Shop supervisor security role (JmgShopSupervisor)
ms:assetid: 38193eb8-7f4e-4817-af21-ceda559da4f4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527079(v=AX.60)
ms:contentKeyID: 37823131
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Shop supervisor security role (JmgShopSupervisor) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Shop supervisor security role represents a user who ensures the day-to-day execution of orders/jobs so Machine operators know what to work on, who is available and can respond to the main requests from Machine operators.

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
<th><p>Duty name</p></th>
<th><p>Duty AOT name</p></th>
<th><p>Duty description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enable kanban execution process</p></td>
<td><p>KanbanExecutionProcessEnable</p></td>
<td><p>Set up policies and reference data to enable lean production and replenishment</p></td>
</tr>
<tr class="even">
<td><p>Inquire into limited worker information</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmLimitedWorkerInquire</p></td>
<td><p>Respond to inquiries about limited worker information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into manufacturing execution progress</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>JmgManufacturingExecutionProgressInquir</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain time supervision</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>JmgTimeSupervisionMaintain</p></td>
<td><p>Document and record time supervision in Time and attendance</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into production orders</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProdProductionOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory adjustment journal entries</p></td>
<td><p>InventProfitLossUpdatesMaintain</p></td>
<td><p>Document and record adjustment entries in inventory adjustment journal</p></td>
</tr>
<tr class="odd">
<td><p>Maintain job corrections in registrations form</p></td>
<td><p>JmgJobRegistrationsCorrectionsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain project journals and journal transactions</p></td>
<td><p>ProjProjectJournalsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain time registration</p></td>
<td><p>JmgTimeRegistrationMaintain</p></td>
<td><p>Document and record time registration in Time and attendance</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

