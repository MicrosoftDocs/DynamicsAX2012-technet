---
title: Quality control manager security role (InventQualityControlManager)
TOCTitle: Quality control manager security role (InventQualityControlManager)
ms:assetid: 30e76aac-2441-497a-a479-7c92330c6c67
ms:mtpsurl: https://technet.microsoft.com/library/Hh527077(v=AX.60)
ms:contentKeyID: 37823129
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Quality control manager security role (InventQualityControlManager) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Quality control manager role represents a user who enables and reviews processes, maintains master data, and responds to inquiries within quality control.

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
<td><p>Inquire into inventory case progress</p></td>
<td><p>CaseInventoryCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of inventory cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into products definition master</p></td>
<td><p>EcoResProductDefinitionMasterInquire</p></td>
<td><p>Respond to inquiries about products definition master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into products for operations master</p></td>
<td><p>EcoResProductForOperationsMasterInquire</p></td>
<td><p>Respond to inquiries about products for operations master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into product change cases</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EngChgCaseInquire</p></td>
<td><p>Respond to inquiries about product change cases</p></td>
</tr>
<tr class="odd">
<td><p>Approve inventory batch movements</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventBatchHandlingApprove</p></td>
<td><p>Approve inventory batch movement events</p></td>
</tr>
<tr class="even">
<td><p>Inquire into batch merges</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventBatchHandlingInquire</p></td>
<td><p>Respond to inquiries about merge operations on inventory batches</p></td>
</tr>
<tr class="odd">
<td><p>Approve nonconformances</p></td>
<td><p>InventNonConformanceApprove</p></td>
<td><p>Approve nonconformance records</p></td>
</tr>
<tr class="even">
<td><p>Approve nonconformance corrections</p></td>
<td><p>InventNonConformanceCorrectionApprove</p></td>
<td><p>Complete and reopen nonconformance corrections</p></td>
</tr>
<tr class="odd">
<td><p>Maintain quality control master</p></td>
<td><p>InventQualityControlMasterMaintain</p></td>
<td><p>Maintain master data for quality control</p></td>
</tr>
<tr class="even">
<td><p>Enable quality control process</p></td>
<td><p>InventQualityControlProcessEnable</p></td>
<td><p>Set up policies and reference data for the quality control process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into quality control progress</p></td>
<td><p>InventQualityControlProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the quality control process</p></td>
</tr>
<tr class="even">
<td><p>Review quality control process performance</p></td>
<td><p>InventQualityCtrlProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the quality control process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="even">
<td><p>Inquire into shipping progress</p></td>
<td><p>InventShippingProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the shipping process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into inventory status</p></td>
<td><p>InventStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the inventory</p></td>
</tr>
<tr class="even">
<td><p>Inquire into tracking dimensions master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventTrackingDimensionsMasterInquire</p></td>
<td><p>Respond to inquiries about tracking dimensions master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain inventory setup print management settings</p></td>
<td><p>PrintMgmtInventParametersSetupMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into reservation hierarchy</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSReservationHierarchyMasterInquire</p></td>
<td><p>Inquire into reservation hierarchy</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into warehouse operation progress</p></td>
<td><p>WMSWarehouseOperationProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the warehouse operation process</p></td>
</tr>
</tbody>
</table>

  


